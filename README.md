# Airbnb-price-predict-20201009-LA
predict airbnb price with 20201009 LA data

colab link :https://colab.research.google.com/drive/136zXQteY5fdm5RpSNzx52WsQpb3g07ln?usp=sharing

In this project, I am trying to predict LA airbnb price with data getting from insideairbnb.com and finally I got a 0.6 r2 score.

There are three sections.

First, I analysize data , drop some feature, transform some feature, and fill some na data.

Second, in order to train model, some feature I do one-hot encode, some huge number I do log transform, and I calculate the loaction as the distance to the all rooms' center. After that, I prepare randomly separate data for ten time because I will do the time test to evaulate the models.

Third, I use six different model to predict. They are Linear Regression, Ridge Regression, Random forest Regression, XGBoost Regression, Neural Network with L1 Regularizers, Neural Network with L2 Regularizers.

In the end, both of Neural Network with L1 Regularizers and Neural Network with L2 Regularizers have the best result. I truely believe there still have a lot of things that I can imporve the result.


Reference:

1.insideairbnb

2.Predicting Airbnb prices with machine learning and location data

3.Predicting Airbnb prices with machine learning and deep learning
