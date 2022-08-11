# Previsão da massa dos peixes - Estudo aprofundado sobre regressões lineares

## Sumário
* [Overview](#overview)
* [Resultados e Conclusões](#Resultados)
* [Tecnologias](#tecnologias)

## Overview
Estimação do peso de peixes a venda. O banco de dados possuem 7 diferentes raças de peixes, com 159 linhas e 7 atributos. O presente estudo focou no estudo aprofundado dos parâmetros que podem afetar a implementação de um algoritmo de regressão linear convenciaonal. 

## Fonte dos Dados
Os dados utilizados na análise são open source e podem ser encontrados no seguinte website: https://www.kaggle.com/datasets/aungpyaeap/fish-market

## Resultados e Conclusões
O presente estudo foi uma ótima oportunidade de revisão principalmente de todo o pré-tratamento necessário para a utilização de algoritmos de regressão linear. Aqui cobrimos o estudo da multicolienaridade (correlação e value inflation factor), análise do resíduo (homocedasticidade e normalidade), transformação e normalização da resposta (boxcox, e teste de normalidade), Standartização das variáveis, dummyficação (One-hot encoding), significância estatística de cada regressor (t-test), significância estatística do modelo (F-statistic, P-statistic), entre muitos outros conceitos fundamentais. Como resultado, o algoritmo final teve um RMSE = 50.6g e um R2 = 0.98 no conjunto de teste.
	
## Tecnologias
Projeto criado com:
* Python: 3.10.4
  * Biblioteca: Numpy, Matplotlib.pyplot, pandas, scipy.stats, seaborn, scikit-learn, patsy, statsmodels
* IDE: Google Colab
* Unix: OS version 18.7.0
* Git and Github
