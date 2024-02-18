<h1 align="center"> Análise de Sentimento em Reviews da Amazon usando NLP </h1>

<p align="center">
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-projeto">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
</p>

<br>

<p align="center">
  <img alt="Projeto DevLinks" src="amazon_reviews_sentiment\.github\yes_no.jpg" width="100%">
</p>

## 🚀 Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias e bibliotecas:

- Python
- Pandas
- NLTK (Natural Language Toolkit)
- Scikit-learn
- Imbalanced-learn
- Matplotlib e Seaborn


## 💻 Projeto

Este projeto tem como objetivo realizar uma análise de sentimentos em reviews coletadas do marketplace da Amazon utilizando técnicas de Processamento de Linguagem Natural (NLP). O foco é desenvolver um modelo capaz de inferir se um review é positivo ou negativo, proporcionando insights sobre a satisfação dos usuários em relação aos produtos ou serviços.

**O projeto é dividido em etapas distintas:**

**Exploração Inicial dos Dados**: Análise inicial do conjunto de dados para compreender a distribuição dos sentimentos.

**Transformação dos Valores Target**: Conversão dos rótulos de sentimentos para valores numéricos.

**Pré-processamento do Texto**: Remoção de pontuações e stopwords para preparar o texto para análise.

**Preparação dos Dados**: Divisão dos dados em conjuntos de treino e teste.

**Treinamento do Modelo**: Utilização de um modelo de Regressão Logística através de um pipeline, incorporando etapas de vetorização e transformação TF-IDF.





## Conclusão

O modelo treinado alcança uma acurácia de 89%, indicando sua eficácia na classificação de sentimentos. A escolha da Regressão Logística é fundamentada na interpretabilidade do modelo, adequada para problemas de classificação binária como este.

Este projeto fornece uma base sólida para análises mais aprofundadas sobre a percepção dos usuários em relação aos produtos da Amazon, podendo ser estendido e adaptado conforme necessário.

