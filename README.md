Projeto: classificador de doenças em folha de café

Modelo de classificação que utiliza método de Rede neural convolucional do Keras e TensorFlow para classificar doenças em plantas de café utilizando foto de folhas doentes. O modelo consegue classificar com boa precisão se a folha é saudável ou se possui doença causada pelo Bicho mineiro (Leucoptera coffeella), pelo fungo da Ferrugem do cafeeiro (Hemileia vastatrix) ou pelo fungo do Phoma.


O Notebook doenças_cafe1.ipynb faz o treinamento do modelo de Rede Neural Convolucional utilizando conjuto de imagens de folhas de café (para treinamento, teste e validação, foram utilziadas as imagens que estão no repositório train).
Dados disponíveis em: [https://www.kaggle.com/datasets/alvarole/coffee-leaves-disease]

A pasta "model.zip", contem o modelo de Rede Neural Convolucional já treinado, podendo ser utilizado para fazer novas classificações.

O Notebook classificador1 utiliza o modelo de treino (armazenado na pasta model) para fazer alguns testes e demonstrações do modelo de classificação.
Para estes testes, foram utilizados imagens novas, que não fazem parte dos dados utilizados no treinamento

Analizando os resultados dos testes feitos, é possivel visualizar que o modelo apresentou boa precisão, conseguindo acertar a classificação de quase 100% para folhas saudáveis ou com Phoma. Para os casos de Bicho mineiro e Ferrugem, o modelo conseguiu fazer previsões com precisão de 78% e 83%, respectivamente.

