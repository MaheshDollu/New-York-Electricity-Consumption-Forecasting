Overview of Time Series Models
1. ARIMA (AutoRegressive Integrated Moving Average)
Purpose: Used for forecasting time series data that can be made stationary through differencing.
Components:
AR: AutoRegressive part.
I: Integrated part (differencing).
MA: Moving Average part.
Implementation: Fit using the ARIMA class from statsmodels.
2. SARIMA (Seasonal ARIMA)
Purpose: Extends ARIMA to handle seasonal patterns in data.
Components:
Adds seasonal parameters to ARIMA: (P, D, Q, S).
Implementation: Fit using the SARIMAX class from statsmodels.
3. Prophet
Purpose: Developed by Facebook, Prophet is designed for forecasting time series data that may have strong seasonal effects and several seasons of historical data.
Components:
Handles seasonalities (daily, weekly, yearly).
Incorporates holidays.
Robust to missing data and shifts in the trend.
Implementation: Fit using the Prophet class from the prophet library.
