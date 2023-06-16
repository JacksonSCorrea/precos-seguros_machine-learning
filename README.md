Este é um projeto de Ciência de Dados que tem como objetivo principal desenvolver um modelo de máquina preditiva de valores de seguros, dadas algumas informações sobre o indivíduo.

O objetivo secundário deste projeto é verificar o desempenho dos algoritmos, em especial aqueles baseados em árvores, frente à dados codificados pelos métodos CatBoostEncoder e OneHotEncoder. Dessa forma, a etapa de análise exploratória não possui volume relevante de insights.

O projeto consiste em três macro-etapas:

* Análise exploratória dos dados, mais simples e com menos insights;
* Pré processamento dos dados com split em dados de treino e teste, codificação de variáveis categóricas utilizando CatBoostEncoder e OneHotEncoder, além da padronização e normalizção dos dados;
* Modelagem de máquinas preditivas, com análise de desempenho do modelo testado com validação cruzada, seleção do modelo mais promissr e tunagem de hiperparâmetros para treinamento e teste de um modelo final.

Foram escolhidos os seguintes algoritmos para a modelagem da máquina preditiva:
* Regressão Linear
* Random Forest
* XGBoost

As métricas principais para avaliação do desempenho dos modelos são o RMSE (raiz do erro médio quadrático) e o Coeficiente de Determinação (R2)


Enjoy!
