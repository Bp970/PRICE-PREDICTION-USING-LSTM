# PRICE-PREDICTION-USING-LSTM
Predict Bitcoin price using LSTM Deep Neural Network in TensorFlow 2 we will build a Deep Neural Network model to predict Bitcoin price based on historical data. Our dataset comes from Yahoo! finance and covers all available data on Bitcoin-USD price. We will represent the Bitcoin-USD price for the last 9 years. Were interested in predicting the closing price for the future.

<a href="https://icons8.com/icon/ovHld7NfgG9g/bitcoin">Bitcoin icon by Icons8</a>

# MODELS
* All models do not allow for operating on sequence data. Fortunately, we can use a special class of Neural Network models known as Recurrent Neural Networks (RNNs) just for this purpose.
* RNNs allow using the output from the model as a new input for the same model. The process can be repeated indefinitely.
* One serious limitation of RNNs is the inability of capturing long-term dependencies in a sequence. One way to handle the situation is by using a Long short-term memory (LSTM) variant of RNN.
* The default LSTM behavior is remembering information for prolonged periods of time.


# Conclusion 

Our proposed model has succeeded to provide the result prediction of bitcoin from the yahoo finance stock market. Our model with time series techniques can produce the results and the results can predict the price for the next days with split the data to train and test that we mention in the article above.
Future research will focus on modified LSTM layers, adding dropout and modified number epochs, and using different instability dataset to test how good the prediction results are or try to use sentiment analysis combined with the LSTM method to see the impact of the uncertainty in value bitcoin.



