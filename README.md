# Pipeline de Aprendizado de Máquina para Previsão de Doenças Cardíacas

Este repositório contém um pipeline completo de aprendizado de máquina para prever doenças cardíacas usando o conjunto de dados de Doenças Cardíacas da UCI. O pipeline é implementado em um Jupyter Notebook e inclui carregamento de dados, pré-processamento, engenharia de recursos, treinamento de modelo, avaliação e funcionalidades de previsão. O projeto é modular, reprodutível e extensível para experimentações futuras.

## Sumário
- [Visão Geral do Projeto](#visão-geral-do-projeto)
- [Funcionalidades](#funcionalidades)
- [Conjunto de Dados](#conjunto-de-dados)
- [Instalação](#instalação)
- [Uso](#uso)
- [Etapas do Pipeline](#etapas-do-pipeline)
- [Resultados](#resultados)
- [Melhorias Futuras](#melhorias-futuras)
- [Contribuição](#contribuição)
- [Licença](#licença)

## Visão Geral do Projeto
Este projeto implementa um pipeline de aprendizado de máquina para prever a presença de doenças cardíacas com base em dados de pacientes. Utiliza um Classificador de Árvore de Decisão e inclui etapas detalhadas de exploração de dados, pré-processamento e avaliação. O pipeline segue boas práticas, com integração opcional de banco de dados para rastreamento de experimentos e visualizações abrangentes para interpretabilidade.

## Funcionalidades
- **Carregamento de Dados**: Obtém o conjunto de dados de Doenças Cardíacas da UCI usando o pacote `ucimlrepo`.
- **Análise Exploratória de Dados (EDA)**: Estatísticas descritivas, análise de correlação e visualizações (gráficos de pizza, histogramas, mapas de calor).
- **Engenharia de Recursos**: Cria a razão colesterol-idade para melhorar o desempenho do modelo.
- **Pré-processamento**: Trata valores ausentes, remove outliers e escala os recursos.
- **Treinamento do Modelo**: Treina um Classificador de Árvore de Decisão com hiperparâmetros configuráveis.
- **Avaliação**: Fornece métricas de precisão, matriz de confusão, relatório de classificação e análise de importância de recursos.
- **Previsão**: Permite previsões em amostras individuais com visualização de probabilidades.
- **Rastreamento de Experimentos**: Integração opcional com banco de dados SQLite para armazenar resultados.
- **Visualização**: Gráficos detalhados para distribuição de dados, efeitos de escalonamento e desempenho do modelo.

## Conjunto de Dados
O pipeline utiliza o [conjunto de dados de Doenças Cardíacas da UCI](https://archive.ics.uci.edu/ml/datasets/heart+disease), que contém 303 amostras com 13 características (como idade, colesterol, pressão arterial) e uma variável alvo binária indicando a presença (1) ou ausência (0) de doença cardíaca.

## Instalação
1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/previsao-doencas-cardiacas.git
   cd previsao-doencas-cardiacas

## Video do Projeto 2
   https://youtu.be/ISiIKGaG7Bo
