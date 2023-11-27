# Classificação de preços de celulares (0, 1, 2 e 3)

### Neste notebook, temos uma base com dados referentes a características de celulares, como: Memória RAM, potência da bateria, WIFI, dentre outros.

**O objetivo desse projeto é:**
- Fazer análises da base.
- Gerar gráficos das colunas (que nos traga informações relevantes).
- Analisar correlações entre as variáveis.
- Normalizar/padronizar dados das colunas com escalas diferentes, para melhor performance de alguns modelos, como o KNN.
- Caso a base possua colunas categóricas, utilizar o OneHotEncoder do Sklearn.
- Criar modelos de Machine Learning capazes de aprender com os dados de treino e gerarem uma previsão para os dados de teste, com as classificações dos preços de celulares, na ordem: 0, 1, 2 e 3. Obs: Estar atento a overfiting, underfiting e data leakage no momento de treinamento do modelo.
- Usar métricas para avaliarmos o desempenho dos modelos. (Obs: Estar atento a overfiting, underfiting, data leakage no momento de treinamento do modelo).
- Gerar as previsões de três modelos diferentes (Árvore de Classificação, Regressão Logística (que também é um modelo de classificsação) e KNN.


**Bibliotecas utilizadas:**
- Pandas 
- Numpy
- Searborn
- Matplotlib
- Sklearn (Para importação de modelos, pré-processamentos e métricas de avaliação)
