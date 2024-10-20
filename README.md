# Stock-Market-Prediction
A neural network model designed using LSTM cells to predict stock market prices.

The data used is the apple shares data over 1600 days. The model is designed so that given a lookback, the model predicts the stock market prices of the next day. The lookback refers to the number of days to consider while making the next prediction.

The model is trained using LSTM cells which is one of the best ways to implement Recurrent Neural Networks(RNNs). The model used in this project consists of two LSTM layers consisting of 100 and 256 LSTM cells. The LSTM layers are followed by a dense layer consisting of the output. 

A graph is plotted to visualize how well the model predicts the prices.
