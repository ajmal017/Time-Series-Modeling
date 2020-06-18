# Time-Series-Modeling

A time series is a series of data points indexed in time order. Most commonly, a time series is a sequence taken at successive equally spaced points in time. Thus it is a sequence of discrete-time data.

Whether we wish to predict the trend in financial markets or electricity consumption, time is an important factor that must now be considered in our models. For example, it would be interesting to forecast at what hour during the day is there going to be a peak consumption in electricity, such as to adjust the price or the production of electricity.
Enter time series. A time series is simply a series of data points ordered in time. In a time series, time is often the independent variable and the goal is usually to make a forecast for the future.

However, there are other aspects that come into play when dealing with time series.

Is it stationary?

Is there a seasonality?

Is the target variable autocorrelated?


**Autocorrelation:**
- Informally, autocorrelation is the similarity between observations as a function of the time lag between them.

**Seasonality**
- Seasonality refers to periodic fluctuations. For example, electricity consumption is high during the day and low during night, or online sales increase during Christmas before slowing down again.

**Stationarity**
- Stationarity is an important characteristic of time series. A time series is said to be stationary if its statistical properties do not change over time. In other words, it has constant mean and variance, and covariance is independent of time.

**How to test if a process is stationary**
- You may have noticed in the title of the plot above Dickey-Fuller. This is the statistical test that we run to determine if a time series is stationary or not. Without going into the technicalities of the Dickey-Fuller test, it test the null hypothesis that a unit root is present.

If it is, then p > 0, and the process is not stationary.

Otherwise, p = 0, the null hypothesis is rejected, and the process is considered to be stationary.


### Tasks:
1. Intro to time series
2. Creating a time series object
3. working with time series
4. Analysing AR model
5. Analysing MA model
6. Analysing ARMA model
7. Analysing ARIMA model
8. Working with ARCH model
9. Working with GARCH model

- Pending:
10. Analysing Auto-ARIMA model


### References:
[Guide to time series analysis](https://towardsdatascience.com/the-complete-guide-to-time-series-analysis-and-forecasting-70d476bfe775)
