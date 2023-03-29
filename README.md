# Bootcamp_Fiap
## BootCamp de Machine Learning**

Desafio do curso de Inteligencia Artificial e Machine Learning da FIAP visando desenvolver uma solução para uma empresa de suprimentos onde a análise de crédito passaria a ser totalmente automatizada no momento da solicitação/pedido

## Lógica usada neste trabalho
Existem alguns desafios principais neste dataset:
* Possui muitos nulos
* Algumas variáveis não são 'inputáveis' por virem de outros setores da empresa
* Alta correlação entre colunas. Portanto, será necessário realizar uma redução de dimensionalidade e tratamento dos dados, primeiramente em colunas que indicam informações que passaram por outros setores da empresa, de forma a permitir um retorno automatizado.

## Fluxo de Desenvolvido
* Análise Exploratória
* Redução da dimensionalidade em colunas que expressem dados de outros processos e com alta correlação
* Tratamento de Dados Faltantes
* Feature engineering
* Clusterização de empresas
* Análise de características dos clusters
* Aplicação dos clusters no dataframe
* LabelEncoding do dataframe
* StandardScaling do dataframe
* Remoção de outliers
* Treino e teste de modelos com GridSearch
