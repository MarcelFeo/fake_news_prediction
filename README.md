# Fake News Prediction - Machine Learning

Este projeto utiliza aprendizado de máquina para prever se uma notícia é verdadeira ou falsa com base em seu conteúdo textual. O objetivo é ajudar a combater a desinformação, fornecendo uma ferramenta automatizada para identificação de fake news.

## Tecnologias Utilizadas

- **Python**: Linguagem principal do projeto.
- **Bibliotecas**:
  - `numpy` e `pandas`: Manipulação de dados.
  - `nltk`: Pré-processamento de texto, incluindo remoção de stopwords e stemming.
  - `sklearn`: Construção e avaliação do modelo de machine learning (Regressão Logística).

## Funcionalidades

1. **Pré-processamento de Texto**:
   - Remoção de stopwords.
   - Aplicação de stemming para normalizar palavras.
2. **Vetorização**:
   - Conversão de texto para vetores numéricos utilizando `TfidfVectorizer`.
3. **Treinamento do Modelo**:
   - Utilização de Regressão Logística para classificação de fake news.
4. **Avaliação do Modelo**:
   - Cálculo da acurácia utilizando o conjunto de teste.

## Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu_usuario/seu_repositorio.git
   ```

2. Instale as dependências:

3. Execute o notebook:
   ```bash
   jupyter notebook fake_news_prediction.ipynb
   ```

## Estrutura do Projeto

- **`fake_news_prediction.ipynb`**: Notebook principal com todo o código do projeto.
- **`data/`**: Diretório para armazenamento do conjunto de dados.

## Conjunto de Dados

Utilize qualquer conjunto de dados de notícias que possua rótulos para verdadeiro/falso. Recomendo o [Kaggle Fake News Dataset](https://www.kaggle.com/c/fake-news/data).

## Resultados

O modelo atinge uma acurácia satisfatória para a tarefa de classificação, demonstrando sua eficácia em identificar notícias falsas com base em padrões linguísticos e contextuais.

---
