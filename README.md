# AdEase-Time_series
This repository contains a comprehensive data science project conducted for Ad Ease, an ads and marketing company specializing in providing businesses with an efficient, cost-effective advertising infrastructure. This project provides a robust framework for predicting audience engagement on Wikipedia pages.

This project involves forecasting Wikipedia page views for 145k pages in multiple languages to optimize ad placements. By leveraging time series models like ARIMA, SARIMAX, and Prophet, we aimed to provide accurate predictions for different regions and languages.

Key Steps
Feature Engineering:Ensured stationarity using the Dickey-Fuller test.

Removed trends and seasonality with differencing.

Modeling:
ARIMA: Initial results showed MAPE = 9% and RMSE = 682, limited by its inability to handle seasonality.
SARIMAX: Improved MAPE to 4.6% and RMSE to 291 by capturing seasonality and using exogenous variables.
Prophet: Achieved MAPE = 6.56%, a balance between ARIMA and SARIMAX.
Results
SARIMAX emerged as the best model, demonstrating the importance of accounting for seasonality and external factors in time series forecasting.

Tech Stack
Python | Pandas | NumPy | ARIMA | SARIMAX | Prophet
This project is a robust example of using advanced forecasting techniques to drive actionable business insights.


