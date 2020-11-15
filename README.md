# Sentiment-Analysis-of-Twitter-Comments-on-US-Airlines
Sentiment analysis is an important job for most US airlines. This notebook is written to build a natural language processing model to analyze sentiment based on twitter text comments on major US airlines. The data source can be found on Kaggle: https://www.kaggle.com/crowdflower/twitter-airline-sentiment. The csv file has been downloaded, which include the columns "text", "airline_sentiment". In the following cells, a model will be built to predict the sentiment (three categories: postive, neutral, negative) based on text comments. TensorFlow is used to build a model including layers of convolutional neural network, recurrent neural network and deep neural network. It has been found out that using dropout layers can significantly improve the overfitting issue. An accuracy of ~0.80 has been achived on the validation data set.
