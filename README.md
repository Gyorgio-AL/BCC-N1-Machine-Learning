# BCC-N1-Machine-Learning

Curso: Ciência de Dados / Inteligência Artificial
Disciplina: Machine Learning e Análise de Dados
Guilherme Estevan Salai |RA:2025113580
Marcos Vinicius Barbosa Nardy | RA: 2025118988                                                                              
Luiz Miguel Rodrigues Ferreira | RA: 2025119022                                                                            
Gyovanni Albuquerque Lopes Vilarino | RA:2025205405                                                
Maycom Souza Fonseca|RA: 090279090
Data: 20/05/2026


1. Introdução
O presente trabalho tem como objetivo desenvolver um sistema de Machine Learning capaz de prever quais clientes possuem maior probabilidade de se tornarem clientes Premium. O projeto foi desenvolvido utilizando Python no ambiente Google Colab, utilizando bibliotecas voltadas para análise de dados, visualização estatística e aprendizado de máquina.

O estudo contempla todas as etapas fundamentais de um projeto de Ciência de Dados, incluindo coleta e tratamento de dados, engenharia de atributos, treinamento do modelo, validação estatística, interpretação dos resultados e aplicação prática para tomada de decisão empresarial.

A proposta principal consiste em demonstrar como técnicas de Inteligência Artificial podem ser aplicadas para otimizar estratégias de marketing, segmentação de clientes e campanhas de conversão.

2. Objetivos

Os principais objetivos deste trabalho são:

Construir uma base de dados simulada de clientes;
Aplicar técnicas de engenharia de atributos;
Desenvolver um modelo supervisionado de classificação;
Avaliar o desempenho do modelo utilizando métricas estatísticas;
Interpretar os resultados obtidos;
Demonstrar aplicações práticas em cenários empresariais.
3. Fundamentação Teórica

Machine Learning é uma área da Inteligência Artificial que permite que sistemas computacionais aprendam padrões a partir de dados sem serem explicitamente programados.

Entre os modelos supervisionados de classificação, o algoritmo Random Forest destaca-se pela robustez, precisão e capacidade de generalização. Esse modelo funciona por meio da combinação de múltiplas árvores de decisão, reduzindo problemas de overfitting e aumentando a estabilidade das previsões.

Além disso, métricas como Acurácia, Precisão, Recall, F1-Score e ROC-AUC são amplamente utilizadas para avaliar modelos de classificação binária.

4. Desenvolvimento do Projeto

Inicialmente, foi criada uma base de dados sintética contendo 1000 registros de clientes. As variáveis consideradas incluem:

Idade;
Renda mensal;
Tempo de relacionamento;
Número de compras anuais;
Valor da última compra;
Participação em programas de fidelidade.

Posteriormente, foi criada a variável alvo denominada “comprou_premium”, representando clientes Premium e clientes Regulares.

Também foram aplicadas técnicas de engenharia de atributos, gerando novas variáveis relevantes para o modelo:

Ticket Médio Estimado;
Engajamento Financeiro relativo à renda.

Esses atributos ajudaram a aumentar a capacidade preditiva do algoritmo.

5. Modelo Utilizado

O algoritmo escolhido foi o Random Forest Classifier, utilizando 150 árvores de decisão e profundidade máxima igual a 8.

A escolha do modelo ocorreu devido às seguintes vantagens:

Alta precisão;
Boa interpretação dos resultados;
Resistência a overfitting;
Excelente desempenho em dados tabulares;
Capacidade de calcular importância das variáveis.

O conjunto de dados foi dividido em:

80% para treinamento;
20% para teste.

A divisão foi realizada de forma estratificada para manter o equilíbrio entre as classes.

6. Avaliação do Modelo

Após o treinamento, o modelo foi avaliado utilizando diversas métricas estatísticas.

As principais métricas utilizadas foram:

Acurácia;
Precisão;
Recall;
F1-Score;
ROC-AUC.

Também foram geradas importantes visualizações:

Matriz de confusão;
Curva ROC;
Curva Precision-Recall;
Heatmap de correlação;
Distribuição de probabilidades.

Essas análises permitiram verificar que o modelo apresentou boa capacidade de separação entre clientes Premium e Regulares.

7. Aplicação Prática

Uma das aplicações práticas desenvolvidas no projeto foi a recomendação automática de clientes com maior potencial de conversão para Premium.

O sistema identificou clientes regulares com alta probabilidade de adesão a produtos Premium, permitindo que campanhas de marketing sejam direcionadas de maneira mais eficiente.

Esse tipo de solução pode ser aplicado em:

Sistemas de CRM;
Estratégias de marketing digital;
Programas de fidelização;
Automação comercial;
Segmentação inteligente de clientes.
8. Resultados Obtidos

Os resultados obtidos demonstraram que o modelo Random Forest apresentou desempenho satisfatório na tarefa de classificação.

As curvas ROC e Precision-Recall mostraram boa separação entre as classes, enquanto a matriz de confusão evidenciou baixo número de erros de classificação.

Além disso, a análise de importância das variáveis mostrou que fatores como renda mensal, número de compras e valor da última compra possuem grande influência no comportamento Premium dos clientes.

9. Conclusão

Conclui-se que o projeto alcançou com sucesso os objetivos propostos, demonstrando a aplicação prática de técnicas de Machine Learning em problemas reais de negócio.

O modelo Random Forest apresentou resultados satisfatórios na classificação de clientes, além de fornecer interpretabilidade por meio da análise de importância das variáveis.

A utilização de Inteligência Artificial para prever comportamento de clientes representa uma importante ferramenta estratégica para empresas modernas, auxiliando na tomada de decisões e aumentando a eficiência operacional.

Como melhorias futuras, recomenda-se:

Teste com novos algoritmos;
Otimização de hiperparâmetros;
Uso de dados reais;
Criação de dashboards interativos;
Implementação em sistemas web ou APIs.
10. Referências
GÉRON, Aurélien. Hands-On Machine Learning with Scikit-Learn, Keras & TensorFlow.
PEDREGOSA, F. et al. Scikit-learn: Machine Learning in Python.
MCKINNEY, Wes. Python for Data Analysis.
Documentação oficial do Scikit-Learn.
Documentação oficial do Pandas.
Documentação oficial do NumPy.
