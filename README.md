# Classificação de Cogumelos: Comestíveis ou Venenosos

Este projeto utiliza dados de cogumelos para prever se uma espécie é comestível (E) ou venenosa (P) com base em suas características. Usamos um classificador de árvore de decisão para realizar as previsões.

## Descrição do Projeto

O dataset utilizado contém informações sobre várias características dos cogumelos, como formato, superfície e cor do chapéu, presença de hematomas, odor, entre outros. A variável alvo é a classe do cogumelo, que indica se ele é comestível (E) ou venenoso (P).

## Estrutura do Projeto

- **Importação de Bibliotecas**: Usamos `pandas`, `numpy`, `seaborn`, `matplotlib` e `plotly.express` para manipulação e visualização de dados, e `scikit-learn` para modelagem de machine learning.
- **Carregamento e Verificação dos Dados**: O dataset é carregado de um arquivo CSV e verificado para assegurar a integridade dos dados.
- **Análise Exploratória de Dados (EDA)**: Visualizações, como o gráfico de barras para a distribuição das classes, são geradas.
- **Pré-Processamento dos Dados**: Conversão das variáveis categóricas em variáveis dummy e separação da variável alvo.
- **Divisão dos Dados**: O conjunto de dados é dividido em subconjuntos de treinamento e teste.
- **Treinamento do Modelo**: Um classificador de árvore de decisão é treinado com o conjunto de treinamento.
- **Visualização da Árvore de Decisão**: A árvore de decisão treinada é visualizada.
- **Previsões e Avaliação**: O modelo faz previsões no conjunto de teste e os resultados são comparados com os valores reais.

## Utilização do Dataset
O dataset usado neste projeto pode ser encontrado [aqui](https://www.kaggle.com/datasets/devzohaib/mushroom-edibility-classification).
