# frankfurt-stock-prediction-using-arima

The dataset contains open high low close stock prices of Frankfurt Stock Exchange. The data is available from 2008 May to 2020 August.
The data is available only for buisiness days.

You can download the dataset from this link https://www.kaggle.com/krishnasrujan/frankfurt-stock-exchange

Analysis done:

The Seasonality and Trend in the data is observed. 
The correlaton and auto correlation plots are plotted to analyze the dependency of present value on previous values.
Choosing the right p,d,q values, arima model is built and forecast is done.

Also Random Forest Regressor is used to predict the closing price. It too gives good predictions with less mean squared error.
