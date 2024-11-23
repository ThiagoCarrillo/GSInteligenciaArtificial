# README
## Renewable Energy Analysis and Classification
Este projeto visa analisar e prever tendências no uso de energia renovável com base em um conjunto de dados global. Ele inclui análise exploratória, visualização de dados, cálculo de métricas de crescimento e classificação das tendências de uso.

## Funcionalidades do Projeto
### Análise Exploratória de Dados (EDA):
Leitura e limpeza de dados para eliminar colunas irrelevantes e valores ausentes.
Descrição estatística das variáveis.
### Visualizações:
Linhas do tempo mostrando a evolução do uso de energia renovável (medido em KTOE) por país.
Taxas médias de crescimento no uso de energia renovável exibidas em gráficos de barras.
### Cálculo de Métricas:
Taxa de crescimento anual por país.
Classificação dos países em três categorias:
Declínio: Crescimento menor que -1%.
Estável: Crescimento entre -1% e 1%.
Crescimento: Crescimento maior que 1%.
### Modelagem e Classificação:
Codificação de variáveis categóricas.
Imputação de valores ausentes.
Treinamento de um modelo Random Forest Classifier para prever categorias de crescimento.
Avaliação do modelo com métricas como acurácia e relatório de classificação.

## Principais Etapas
### Carregar e Preparar os Dados:
O arquivo CSV é carregado e colunas irrelevantes são removidas.
### Análise e Visualização:
Dados filtrados para medir apenas valores de energia renovável (unidade: KTOE).
Gráficos mostram a evolução temporal e taxas de crescimento.
### Modelagem:
Variáveis categóricas transformadas para um formato numérico.
Dados divididos em conjuntos de treino e teste para treinamento do modelo de classificação.
### Avaliação:
O desempenho do modelo é avaliado com métricas como acurácia e relatório de classificação.

## Saídas Principais
### Gráficos:
Evolução temporal do uso de energia renovável por país.
Taxas médias de crescimento no uso de energia renovável.
### Relatórios:
Estatísticas detalhadas sobre o dataset.
Relatório de classificação do modelo de Machine Learning.
### Acurácia do modelo.

## LINK DO VIDEO: https://www.youtube.com/watch?v=rScpvf31ZMA

#### Thiago Carrillo RM553565 - 2TDSPS
#### Igor Oviedo RM553434 - 2TDSPS
#### Cauã Loureiro RM553093 - 2TDSPS
