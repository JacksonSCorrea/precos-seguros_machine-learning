Este é um projeto introdutório ao Aprendizado de Máquina e à Regressão Linear.
O intuito foi replicar um exemplo existente na plataforma Kaggle, porém, implementando algumas tentativas de elevar o Coeficiente de Determinação (R²).
É possível observar no quadro resumo que consta no notebook que as tentativas não foram bem sucedidas, sendo o modelo baselineo de melhor desempenho em relação ao R².
As ações utilizadas para a tentativa de otimização do modleo foram:
- Estratificação dos dados de treinamento
- Criação de nova variável com o intuito de penalizar ou gratificar algumas instâncias, tornando mais evidente a discrepância de valores do seguro entre elas.
- Avaliação e remoção de outliers da variável target.

Ao fim do código é implementado um script, baseado no modelo de partida, para a previsão de valores de novos seguros.
Um dataframe resumo é exibido, mostrando o R² e o RMSE de cada modelo trabalhado no projeto.

Enjoy!
