# Forecasting US Retail Sales growth using an ARIMA model

## Method

### This project uses an ARIMA model to forecast retail sales growth in the US. 
### I first conduct stationarity tests, and then fit two models. The first is chosen based on the ACF and PACF, and the second is chosen to minimise the AIC. 
### I used data from 1992 to 2022 for training, and then compare the out of sample forecasts for the actual values for January 2023 to April 2024.

## Results

### The model which minimises the AIC has a lower RMSE, however both models fail to predict the direction and magnitude of the swings in retail sales growth.

## Data

### US retail sales data was downloaded from FRED: https://fred.stlouisfed.org/series/RSXFS


