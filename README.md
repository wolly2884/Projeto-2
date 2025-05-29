# Esteira de Aprendizado de Máquina

## Descrição do Projeto

Este projeto implementa uma esteira básica de aprendizado de máquina em um notebook Python (`.ipynb`). A esteira abrange as etapas essenciais de um fluxo de trabalho de ML, incluindo:

1.  **Carregamento de Dados**: Utiliza um conjunto de dados de exemplo (Iris) para demonstração, mas é facilmente adaptável para qualquer arquivo CSV.
2.  **Análise Descritiva**: Apresenta estatísticas gerais e informações sobre o dataset.
3.  **Transformação de Colunas**: Demonstra a criação de uma nova feature a partir de colunas existentes.
4.  **Transformação de Linhas**: Realiza uma filtragem de dados para remover potenciais outliers.
5.  **Divisão de Subconjuntos**: Separa o dataset em conjuntos de treinamento, validação e testes.
6.  **Treinamento e Avaliação do Modelo**: Treina um modelo de classificação (Árvore de Decisão) e o avalia em um conjunto de validação.
7.  **Métricas de Desempenho**: Apresenta a matriz de confusão e a acurácia do modelo no conjunto de testes.
8.  **Predição de Exemplo**: Demonstra como usar o modelo treinado para fazer uma predição em uma nova amostra.

## Como Reproduzir a Execução

Para reproduzir a execução deste projeto, siga os passos abaixo:

### Pré-requisitos

* Python 3.x instalado.
* Jupyter Notebook ou JupyterLab (recomendado para `.ipynb`). Alternativamente, você pode usar Google Colab.

### Bibliotecas Necessárias

As seguintes bibliotecas Python são utilizadas:

* `pandas`
* `numpy`
* `scikit-learn`
* `matplotlib`
* `seaborn`

Você pode instalá-las usando pip, se ainda não as tiver:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn