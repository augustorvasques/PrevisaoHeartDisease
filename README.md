# PrevisaoHeartDisease
Projeto dedicado à análise de dados históricos de pacientes sobre ter ou não doença cardíaca, e criação de modelo para previsão da condição de novos pacientes com base nas informações fornecidas. Foi todo desenvolvido em Python, com a parte de ETL, análise exploratória, remoção de registros dupicados e outliers, além de testes de modelo de Machine Learning de aprendizagem supervisionada e posterior comparação entre os desempenhos obtidos por cada algoritmo.

A melhor solução obtida inincialmente foi de um modelo linear (LogisticRegression) e para entender melhor a tomada de decisão, foi plotado um gráfico com os coeficientes atingidos por cada feature (variável explicativa) do problema.
![image](https://github.com/augustorvasques/PrevisaoHeartDisease/assets/166548437/981132d5-9d5f-475b-a41f-c566e509f2f6)

A segunda melhor solução obtida foi de um modelo não linear (RandomForestClassifier), que para entender melhor sua tomada de decisão foi plotado um gráfico da importância assumida por cada variável durante o processo de exploração.
![image](https://github.com/augustorvasques/PrevisaoHeartDisease/assets/166548437/782a8842-5706-4da1-a9dd-566ecfdfe5e4)

Por fim, por se tratar de modelos com tomadas de decisão por diferentes análises, foi criado um Ensemble, ou seja, um modelo com os dois modelos acima combinados, cada um com sua contribuição para a decisão final.
Dessa forma, foi obtido o modelo com melhor acurácia entre todos os testados: atingindo 84,21% de precisão.

No arquivo 'solucaoexplicada' em anexo, está disponível o passo a passo com explicação mais detalhada.
