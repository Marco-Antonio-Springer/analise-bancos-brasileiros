# Análise do Desempenho de Bancos Brasileiros

## Objetivo

Comparar o desempenho histórico das ações de quatro bancos brasileiros: Itaú, Bradesco, Santander e Banco do Brasil.

## Ativos analisados

* Itaú: ITUB4.SA
* Bradesco: BBDC4.SA
* Santander: SANB11.SA
* Banco do Brasil: BBAS3.SA

## Metodologia

O projeto utiliza Python para obter e organizar dados históricos de ações, construir um índice de desempenho com base 100 e visualizar a evolução dos ativos em um gráfico de linhas.

O índice permite comparar a variação das séries ao longo do período analisado, mesmo quando os preços iniciais das ações são diferentes.

O gráfico também destaca três referências históricas: a pandemia de COVID-19, o início do ciclo de alta da Selic em 2021 e o caso Americanas em 2023. Essas marcações servem como contexto para a análise e não demonstram, por si só, causalidade sobre os movimentos das ações.

## Ferramentas

* Python
* yfinance
* pandas
* Matplotlib

## Fonte dos dados

Yahoo Finance, por meio da biblioteca `yfinance`.

## Limitações

A comparação histórica não substitui uma análise fundamentalista das instituições. O desempenho passado não garante resultados futuros, e o gráfico não isola os efeitos de cada acontecimento econômico sobre as ações.

## Finalidade

Projeto educacional desenvolvido para praticar programação, coleta de dados financeiros, visualização de dados e análise do mercado de capitais.

## Gráfico de Desempenho 
![Desempenho histórico das ações dos bancos](desempenho_bancos.png)