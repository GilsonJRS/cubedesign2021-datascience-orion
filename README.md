# Cube Design 2021 - Desafio DataScience - Equipe Orion Aerospace Design

A categoria DataScience da competição CubeDesign tinha como desafio a análise dos dados de telemetria do CubeSat brasileiro Nanosatc-br2.

Neste repositório temos o notebook com todo o trabalho desenvolvido pela equipe da área de Computação da Orion nesse desafio.

## Dados

Na pasta data estão disponiveis os dados utilizados, sendo eles os de telemetria, disponibilizados na plataforma Kaggle(cubedesign_train.csv e cubedesign_test.csv), os dados do repositório Zenodo(data_from_ncbr2.csv), o arquivo de TLEs do NanoSsatc-br2(nanobr2_tle.csv). Na pasta raiz temos também o arquivo de efeméride(de421.bsp) necessário para nosso calculo da posição do satélite em relação a luz solar.

## Execução 

O notebook pode ser executado localmente, observando que existem dependências que devem ser resolvidas para a correta execução. Estas depêndencias estão no arquivo requirements.txt.

A execução também pode ser realizada no Binder, simplesmente acessando a ferramenta pelo badge abaixo. Neste caso, uma instância do JupyterHub sera criada, com todas as depêndencias já resolvidas.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/GilsonJRS/cubedesign2021-datascience-orion/main?labpath=CubeDesign_notebook.ipynb)