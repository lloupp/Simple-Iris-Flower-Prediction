# Simple Iris Flower Prediction App

Este é um aplicativo simples de previsão de **flores Iris** que utiliza a biblioteca Streamlit para criar uma interface gráfica do usuário para prever o tipo de flor de acordo com as entradas do usuário.

## Como utilizar o aplicativo

O usuário pode selecionar as características da flor, incluindo o comprimento e a largura da sépala e do pétala, deslizando os controles deslizantes na barra lateral. As características selecionadas serão exibidas na seção "User Input parameters".

Em seguida, o aplicativo utiliza um modelo de classificação de floresta aleatória (Random Forest Classifier) treinado com o conjunto de dados Iris, disponível na biblioteca de datasets do scikit-learn, para prever o tipo de flor com base nas características fornecidas pelo usuário.

O resultado da previsão será exibido na seção "Prediction", com a probabilidade da previsão sendo exibida na seção "Prediction Probability".

# Pré-requisitos
Python 3.x
Bibliotecas Streamlit, Pandas e scikit-learn

## Como executar o aplicativo

1. Clone o repositório em sua máquina local.
2. Abra um terminal e navegue até o diretório do aplicativo.
3. Execute o seguinte comando para instalar as dependências necessárias:

'''
pip install streamlit pandas scikit-learn
'''
* Em seguida, execute o seguinte comando para executar o aplicativo:
'''
streamlit run iris_app.py
'''
## Sobre o conjunto de dados Iris
O conjunto de dados Iris é um dos conjuntos de dados mais populares em aprendizado de máquina e classificação. Ele consiste em 150 amostras de flores Iris com medidas de comprimento e largura da sépala e do pétala. Cada amostra é rotulada com uma das três espécies de flores Iris: Iris setosa, Iris virginica ou Iris versicolor. O conjunto de dados é frequentemente utilizado para fins de aprendizado de máquina de classificação, incluindo a previsão de espécies de flores Iris com base em suas características.
## Sobre o modelo de classificação de floresta aleatória
O modelo de classificação de floresta aleatória é um algoritmo de aprendizado de máquina supervisionado que pode ser utilizado para tarefas de classificação e regressão. Ele é uma extensão da árvore de decisão, onde várias árvores de decisão são criadas em paralelo e seus resultados são combinados para produzir a previsão final.

No caso deste aplicativo, um modelo de classificação de floresta aleatória é utilizado para prever o tipo de flor Iris com base nas características fornecidas pelo usuário. O modelo é treinado com o conjunto de dados Iris disponível na biblioteca scikit-learn.

## Sobre a biblioteca Streamlit
A biblioteca Streamlit é uma ferramenta de código aberto para a criação de aplicativos da web de ciência de dados em Python. Com o Streamlit, é possível criar interfaces gráficas de usuário para aplicativos de aprendizado de máquina e visualização de dados de forma rápida e fácil.

Neste aplicativo, o Streamlit é utilizado para criar a interface do usuário e exibir os resultados da previsão.

# Conclusão
Este é um aplicativo simples, mas útil, que permite prever o tipo de flor Iris com base nas características fornecidas pelo usuário. Ele utiliza um modelo de classificação de floresta aleatória treinado com o conjunto de dados Iris disponível na biblioteca scikit-learn e a biblioteca Streamlit para criar a interface do usuário. Com este aplicativo, os usuários podem explorar como os modelos de aprendizado de máquina podem ser utilizados para previsões em tempo real e para a construção de aplicativos interativos e úteis para tarefas do mundo real.
