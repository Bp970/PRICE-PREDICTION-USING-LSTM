# PRICE-PREDICTION-USING-LSTM
Predict Bitcoin price using LSTM Deep Neural Network in TensorFlow 2
we will build a Deep Neural Network model to predict Bitcoin price based on historical data. Our dataset comes from Yahoo!finance and covers all available data on Bitcoin-USD price. We will representing Bitcoin-USD price of last 9 years. Were interested in predicting the closing price for future dates.
![image](https://user-images.githubusercontent.com/69081864/142363040-045a0be7-68a8-443a-8c40-5d50a2ae4704.png)



All models do not allow for operating on sequence data. Fortunately, we can use a special class of Neural Network models known as Recurrent Neural Networks (RNNs) just for this purpose. RNNs allow using the output from the model as a new input for the same model. The process can be repeated indefinitely.
One serious limitation of RNNs is the inability of capturing long-term dependencies in a sequence. One way to handle the situation is by using an Long short-term memory (LSTM) variant of RNN.
The default LSTM behavior is remembering information for prolonged periods of time.

![image](https://user-images.githubusercontent.com/69081864/142363143-34388b40-93a5-42b9-b9cc-d1fee5e471da.png)

Since Bitcoin and the Blockchain technology were introduced in 2008,  it has taken a pre-
dominant place in the cryptocurrency field.  There are millions of users around the world,
especially in the United States.  Predicting the price of cryptocurrencies has been a popular
topic, from which we can take advantage of the arbitrage for an investment
Cryptocurrency price prediction using LSTMs by utilizing the recurrent neural network. The model is developed using LSTM and achieves higher precision and recall than the traditional autoregressive approach. This Cryptocurrency price prediction using LSTMs can be used to predict the price fluctuation of the cryptocurrency and integrated to an autonomous trading system to assist the buying or selling of digital assets.

![image](https://user-images.githubusercontent.com/69081864/142363178-89576c1c-e32a-44ca-a812-51a8ce9a39da.png)



#Conclusion 

Our proposed model has succeeded to provide the result prediction of bitcoin from yahoo finance stock market. Our model with time series techniques can produce the results and the results can predict the price for the next days with split the data to train and test that we mention in the article above.
Future research will focus on modified LSTM layers, adding dropout and modified number epochs, and using different instability dataset to test how good the prediction results or try to use sentiment analysis combined with LSTM method to see the impact of the uncertainty in value bitcoin. 


![image](https://user-images.githubusercontent.com/69081864/142363218-e4bee83a-3965-45c7-8828-d805883018d1.png)
