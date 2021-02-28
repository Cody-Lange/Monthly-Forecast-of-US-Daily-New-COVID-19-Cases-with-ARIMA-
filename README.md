# Monthly-Forecast-of-US-Daily-New-COVID-19-Cases-with-ARIMA-

At the time of writing this, 28,212,548 cases of COVID-19 have been reported in the USA. Flustered with what is seemingly an endless pandemic, I am putting my data science skills to the test to see if I can predict the trajectory of this public health crisis over the next 30 days.

To do so, I will be using time series data of US daily new COVID-19 cases made publicly available by Johns Hopkins University: https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_time_series. Data is imported and manipulated, checked for stationarity. Autocorrelation and partial autocorrelation function plots are created to get a sense of how observations are correlated, grid search is conducted find optimized parameters for prediction, and an AutoRegressive Integrated Moving Average (ARIMA) model is used to test and predict 30 day forecasts of daily new COVID-19 cases in the United States.
