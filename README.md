# PrevisaoHeartDisease
Projeto dedicado à análise de dados históricos de pacientes sobre ter ou não doença cardíaca, e criação de modelo para previsão da condição de novos pacientes com base nas informações fornecidas. Foi todo desenvolvido em Python, com a parte de ETL, análise exploratória, remoção de registros dupicados e outliers, além de testes de modelo de Machine Learning de aprendizagem supervisionada e posterior comparação entre os desempenhos obtidos por cada algoritmo.

A melhor solução obtida inincialmente foi de um modelo linear (LogisticRegression) e para entender melhor a tomada de decisão, foi plotado um gráfico com os coeficientes atingidos por cada feature (variável explicativa) do problema.
![image](https://github.com/augustorvasques/PrevisaoHeartDisease/assets/166548437/981132d5-9d5f-475b-a41f-c566e509f2f6)

A segunda melhor solução obtida foi de um modelo não linear (RandomForestClassifier), que para entender melhor sua tomada de decisão foi plotado um gráfico da importância assumida por cada variável durante o processo de exploração.
