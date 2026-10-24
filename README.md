# Modelo de Jogo

Projeto que analisa dados de desempenho coletivo das equipes das cinco principais ligas nacionais de futebol da Europa na temporada 2021/22. O trabalho utiliza Python para preparar e enriquecer os dados, aplicar técnicas de normalização e redução de dimensionalidade e agrupar equipes com características de jogo semelhantes por meio de machine learning.

## Objetivos

- Analisar indicadores de desempenho coletivo das equipes das principais ligas nacionais europeias.
- Identificar padrões e semelhanças entre os estilos de jogo das equipes.
- Aplicar técnicas de redução de dimensionalidade e agrupamento para explorar os dados.
- Utilizar visualizações para facilitar a interpretação dos resultados.

## Tecnologias utilizadas

- **Python:** processamento e análise dos dados.
- **Pandas e NumPy:** manipulação e preparação dos dados.
- **Scikit-learn:** normalização, PCA e aplicação do algoritmo KMeans.
- **Matplotlib e Seaborn:** visualização e análise dos dados.
- **Plotly:** criação de visualizações interativas em 2D e 3D.

## Metodologia

O projeto envolve a preparação e o enriquecimento dos dados, a normalização dos indicadores com MinMaxScaler e a aplicação de PCA (*Principal Component Analysis*) para reduzir a dimensionalidade dos dados. Em seguida, o algoritmo KMeans é utilizado para agrupar as equipes, com o número de clusters definido a partir do método do cotovelo.

Os resultados são explorados por meio de visualizações e análises dos grupos identificados, buscando compreender as semelhanças entre os modelos de jogo das equipes.

## Arquivos do projeto

- `Codigo_Modulo12_Modelo de Jogo_Grupo1_MBDAF.ipynb`: notebook Jupyter com as etapas de preparação, análise, modelagem e visualização dos dados.
- `Relatorio_Modulo12_Modelo de Jogo_Grupo1_MBDAF.pdf`: relatório com a apresentação do projeto e seus resultados.

## Contexto

Projeto desenvolvido como trabalho final do Módulo 12 do mestrado em Big Data Aplicado ao Futebol.
