# Vendas_Analise

Trabalho feito para o curso de "Ciência de Dados e Analytics". Formato de Python Notebook comentado. Notebook principal melhor visualizado no Google Colab .

Análise exploratória e pré-processamento de dados de vendas que foca em material de escritório (https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting , 9800 linhas e 17 atributos). Agrupando os pedidos por data, é feita uma análise da soma das vendas por dia e verificada sua variação em função do dia da semana e de feriados/dias-úteis, resultando em uma série histórica. No final é feita uma parte da preparação que será necessária para a previsão das vendas futuras com modelos de Machine Learning.

O notebook é dividido em cinco partes:
- Carregamento do dataset e identificação de problemas (análise inicial)
- Tratamento dos problemas identificados e adição de colunas auxiliares (tratamento dos dados)
- Análise mais profunda e extensa dos dados (análise exploratória)
- Tratamento do dataframe visando implementação de machine learning (pré-processamento)
- Conclusão

Características do problema e técnicas relevantes utilizadas:
- Série histórica de vendas
- Análise exploratória
- Tratamento de dados (inclusive de strings e datas)
- Remoção e inferência de dados
- Visualização de dados
- Pré-processamento de dados para Machine Learning
- Tratamento de outliers
- Auto-correlação (lag) de série histórica
- Normalização

O treinamento de um modelo de machine learning que utiliza os dados deste projeto se encontra na primeira parte do seguinte projeto: https://github.com/flaviohds/MVP_Machine_Learning.
