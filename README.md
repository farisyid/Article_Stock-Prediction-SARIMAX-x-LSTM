# Article_Stock-Prediction-SARIMAX-x-LSTM
![Screenshot 2023-11-21 154241](https://github.com/farisyid/Article_Stock-Prediction-SARIMAX-x-LSTM/assets/142249730/3656288b-bfa9-4a2a-99df-022b65ec5f42)

In this opportunity I will make an article about making timeseries predictions with the object of stock prices by comparing libraries from **Statsmodels** ARIMA, SARIMAX and **Tensorflow** Long Short Term Memory (LSTM). In making timeseries predictions I use the **yfinance** library to get the market share price of **United Tractor** as an example. Please note that **this article is made only to educate readers not as a professional investment advisor**. 

## **ARIMA and SARIMAX**
In ARIMA and SARIMAX modelling in the p d q search segment I compared my findings from the ACF and PACF graphs with auto_arima in the pmdarima.arima library which found the best p d q combination.
![image](https://github.com/farisyid/Article_Stock-Prediction-SARIMAX-x-LSTM/assets/142249730/47e28bdf-5b3d-478e-8cc6-6594b2335cc0)

The graph shows the results of stock price predictions using ARIMA and SARIMAX.

## **LSTM**
In LSTM modelling for the time window I used the number 22 where 22 is the number of working days in each month of the stock market.
![image](https://github.com/farisyid/Article_Stock-Prediction-SARIMAX-x-LSTM/assets/142249730/3bd8bf00-7501-47cc-8e1c-e51796d5b5e0)
The graph shows the results of stock price predictions using LSTM.

## **Conclusion**
From the results of the three models, the LSTM model has the smallest MAPE and RMSE results, it is due to the detailed workings of LSTM at each seasonal time that occurs and requires more parameters to achieve the best model, ARIMA and SARIMAX are no worse, it's just that if used with a long data set requires more accuracy to determine the parameters.
