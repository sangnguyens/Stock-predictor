# Stock-predictor
## Introduction
Stock price analysis has been a critical area of research and is one of the top applications of machine learning. This tutorial will show you how to perform stock price prediction using machine learning. Here, you will use `prophet` to train model with stocks data and deploy model.

## Stock market?
A stock market is a public market where you can buy and sell shares for publicly listed companies. The stocks, also known as equities, represent ownership in the company. The stock exchange is the mediator that allows the buying and selling of shares.
![image](https://user-images.githubusercontent.com/104602469/181874782-e6310432-693a-428e-816a-9e8aeb0b4f3c.png)

## Stock Price Prediction
Stock Price Prediction using machine learning helps you discover the future value of company stock and other financial assets traded on an exchange. The entire idea of predicting stock prices is to gain significant profits. Predicting how the stock market will perform is a hard task to do. There are other factors involved in the prediction, such as physical and psychological factors, rational and irrational behavior, and so on. All these factors combine to make share prices dynamic and volatile. This makes it very difficult to predict stock prices with high accuracy.

# Rubic

1. How does the Prophet Algorithm differ from an LSTM?
	Prophet Algorithm was designed for business timeseries forcasting.
	LSTM in neural network has been designed to process sequence data so its application is not only for timeseries but also for sequence data like text.

2. Why does an LSTM have poor performance against ARIMA and Prophet for Time Series?
	In term of algorithm: LSTM has more hyperparameters to tune than ARIMA and Prophet so that it's hard to make a good model.  
	In term of data: time series normally has seasonality and Prophet or ARIMA was designed to do this task, so that why they work better than LSTM in general.

3. What is exponential smoothing and why is it used in Time Series Forecasting?
	Exponential smoothing is a rule of thumb technique for smoothing time series data using the exponential window function. Whereas in the simple moving average the past observations are weighted equally, exponential functions are used to assign exponentially decreasing weights over time. Time Series might contains seasonality so that why this method is used for Time Series forecasting.

4. What is stationarity? What is seasonality? Why Is Stationarity Important in Time Series Forecasting?
	Stationary: is one whose properties do not depend on time at which the series observed. In this case, the data contains cycles but the length is not fixed. Stationary time series is important because it will have no predictable patterns in the long-term.
	Seasonality: is one whose properties are seasonal the cycles in series have fixed length.

5. How is seasonality different from cyclicality? 
	- The difference between seasonal and cyclical behavior has to do with how regular the period of change is. A seasonal behavior is very strictly regular, meaning there is a precise amount of time between the peaks and troughs of the data.
	- Cyclical behavior on the other hand can drift over time because the time between periods isn't precise.

Fill in the blanks:
`Seasonality` is predictable, whereas `cyclicality` is not.
