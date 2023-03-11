#Simple Iris Flower Prediction App

Este é um aplicativo simples de previsão de **flores Iris** que utiliza a biblioteca Streamlit para criar uma interface gráfica do usuário para prever o tipo de flor de acordo com as entradas do usuário.

#Como utilizar o aplicativo

O usuário pode selecionar as características da flor, incluindo o comprimento e a largura da sépala e do pétala, deslizando os controles deslizantes na barra lateral. As características selecionadas serão exibidas na seção "User Input parameters".

Em seguida, o aplicativo utiliza um modelo de classificação de floresta aleatória (Random Forest Classifier) treinado com o conjunto de dados Iris, disponível na biblioteca de datasets do scikit-learn, para prever o tipo de flor com base nas características fornecidas pelo usuário.

O resultado da previsão será exibido na seção "Prediction", com a probabilidade da previsão sendo exibida na seção "Prediction Probability".

Pré-requisitos
Python 3.x
Bibliotecas Streamlit, Pandas e scikit-learn
Como executar o aplicativo
Clone o repositório em sua máquina local.
Abra um terminal e navegue até o diretório do aplicativo.
Execute o seguinte comando para instalar as dependências necessárias:
