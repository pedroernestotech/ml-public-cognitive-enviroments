# Cognitive Enviroments
 
## Exercício Final

# Classificador de Texto e Classificador com Streamlit

## Visão Geral

Este projeto envolve o desenvolvimento de um classificador de texto utilizando técnicas de machine learning no Python e a criação de um aplicativo Streamlit para interação do usuário. O objetivo é classificar textos em categorias predefinidas com base em seus conteúdos.

## Notebook de Análise e Modelagem

### `notebook_classificacao.ipynb`

Este Jupyter Notebook contém o código e as análises iniciais para o desenvolvimento do modelo de classificação de texto. Inclui etapas de pré-processamento de dados, vetorização de texto, treinamento de modelo e avaliação de desempenho.

#### Etapas Principais:

1. **Limpeza dos Dados**: Aplicação de uma função de limpeza para remover caracteres especiais e números dos textos.
2. **Separação dos Dados**: Divisão dos dados em conjuntos de treinamento e teste.
3. **Vetorização de Texto**: Transformação dos textos em vetores TF-IDF para análise.
4. **Modelagem**: Utilização do RandomForestClassifier para treinar o modelo com os dados processados.
5. **Avaliação do Modelo**: Avaliação do desempenho do modelo usando métricas como precisão, recall e F1-Score.

### Insights Principais:

- O notebook fornece uma visão detalhada do processo de tratamento e modelagem dos dados, incluindo a seleção de características e a escolha do algoritmo de machine learning.
- A análise de métricas de desempenho, como o F1-Score, é essencial para validar a eficácia do modelo.

## Aplicativo Streamlit

O aplicativo Streamlit permite aos usuários fazer upload de arquivos Excel contendo textos para classificação e visualizar os resultados. É uma interface interativa que facilita a interação com o modelo de classificação.

### Como Usar o Aplicativo

1. Acesse o URL do aplicativo: [https://app-fiap-eepezdrkdqjburhi8nvees.streamlit.app/](https://app-fiap-eepezdrkdqjburhi8nvees.streamlit.app/)
2. Faça upload de um arquivo Excel (`Base_classificacao_VIDA.xlsx`) contendo os textos que deseja classificar.
3. O aplicativo processa os dados e exibe os resultados da classificação, incluindo métricas de desempenho.

## Instalação e Execução

### Requisitos

Para executar o notebook e o aplicativo localmente, é necessário instalar as seguintes dependências:

```plaintext
streamlit==1.8.0
pandas==1.4.2
scikit-learn==1.0.2
openpyxl==3.0.9
numpy==1.22.3
