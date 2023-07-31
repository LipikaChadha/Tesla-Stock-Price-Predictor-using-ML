# Tesla-Stock-Price-Predictor-using-ML

Predicting stock prices for TESLA by using ML techniques.

Two approaches were used for this task-
1) ARIMA(Autoregressive Integrated Moving Average), a popular time-series forecasting model used for making predictions based on past data.
2)  LSTM (Long Short-Term Memory) which is a type of recurrent neural network architecture used for processing sequential data, capable of learning long-term dependencies and avoiding the vanishing gradient problem.

Dataset Selection:
Since this task is a forecasting task the time component is critical in this process, as it captures the trends, patterns, and seasonality that may exist in the data.
Most of the Kaggle datasets I looked at had a lot of missing values for the date column. The missing date values would have caused a problem in forecasting tasks.
That’s why I used Quandl to retrieve Tesla's daily stock price data for the last 10 years. Quandl provides access to a wide range of financial and economic data, including stock price data.

