Projeto: classificador de doenças em folha de café

Modelo de classificação que utiliza método de Rede neural convolucional do Keras e TensorFlow para classificar doenças em plantas de café utilizando foto de folhas doentes. O modelo consegue classificar com boa precisão se a folha é saudável ou se possui doença causada pelo Bicho mineiro (Leucoptera coffeella), pelo fungo da Ferrugem do cafeeiro (Hemileia vastatrix) ou pelo fungo do Phoma.

https://github.com/fredstrey/convolutional-neural-network-/blob/main/doen%C3%A7as_cafe1.ipynb


O Notebook doenças_cafe1.ipynb faz o treinamento do modelo de Rede Neural Convolucional utilizando conjuto de imagens de folhas de café (para treinamento, teste e validação, foram utilziadas as imagens que estão no repositório train).
Dados disponíveis em: [https://www.kaggle.com/datasets/alvarole/coffee-leaves-disease]

A pasta "30.zip", contem o modelo de Rede Neural Convolucional já treinado, podendo ser utilizado para fazer novas classificações.

O Notebook classificador1 utiliza o modelo de treino (armazenado na pasta model) para fazer alguns testes e demonstrações do modelo de classificação.
Para estes testes, foram utilizados imagens novas, que não fazem parte dos dados utilizados no treinamento

Analizando os resultados dos testes feitos, é possivel visualizar que o modelo apresentou boa precisão, conseguindo acertar a classificação de quase 100% para folhas saudáveis ou com Phoma. Para os casos de Bicho mineiro e Ferrugem, o modelo conseguiu fazer previsões com precisão de 78% e 83%, respectivamente.

Projeto: classificador de câncer de pele

modelo classifica tumores em malignos ou benignos através de imagem. O modelo utiliza redes neurais convolucionais e conseguiu prever corretamente em média 89% dos casos. Com mais épocas de treinamento e modificações do modelo da rede, é possivel melhorar os resultados.

https://github.com/fredstrey/convolutional-neural-network-/blob/main/cancer.ipynb

O modelo do treinamento foi salvo na pasta "model.zip", data base retirado do Kaggle: https://www.kaggle.com/datasets/hasnainjaved/melanoma-skin-cancer-dataset-of-10000-images
