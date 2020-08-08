# Time-Series
Instructions

Time-Series Forecasting
In this notebook, you will load historical Dollar-Yen exchange rate futures data and apply time series analysis and modeling to determine whether there is any predictable behavior.
Follow the steps outlined in the time-series starter notebook to complete the following:

Decomposition using a Hodrick-Prescott Filter (Decompose the Settle price into trend and noise).
Forecasting Returns using an ARMA Model.
Forecasting the Settle Price using an ARIMA Model.
Forecasting Volatility with GARCH.

Use the results of the time series analysis and modeling to answer the following questions:

Based on your time series analysis, would you buy the yen now?
Is the risk of the yen expected to increase or decrease?
Based on the model evaluation, would you feel confident in using these models for trading?


Linear Regression Forecasting
In this notebook, you will build a Scikit-Learn linear regression model to predict Yen futures ("settle") returns with lagged Yen futures returns and categorical calendar seasonal effects (e.g., day-of-week or week-of-year seasonal effects).
Follow the steps outlined in the regression_analysis starter notebook to complete the following:

Data Preparation (Creating Returns and Lagged Returns and splitting the data into training and testing data)
Fitting a Linear Regression Model.
Making predictions using the testing data.
Out-of-sample performance.
In-sample performance.

Use the results of the linear regression analysis and modeling to answer the following question:

Does this model perform better or worse on out-of-sample data compared to in-sample data?

