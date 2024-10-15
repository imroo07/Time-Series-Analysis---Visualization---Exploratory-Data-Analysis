# Time Series Analysis & Visualization

Time series data is a sequential arrangement of data points organized in consecutive time order. Time-series analysis consists of methods for analyzing time-series data to extract meaningful insights.

# Basics of Time Series Data

**Trend:** A trend represents the general direction in which a time series is moving over an extended period.

**Seasonality:** Seasonality refers to recurring patterns or cycles that occur at regular intervals within a time series, often corresponding to specific time units like days, weeks, months, or seasons.

**Moving average:** The moving average method is a common technique used in time series analysis to smooth out short-term fluctuations and highlight longer-term trends or patterns in the data.

**Noise:** Noise, or random fluctuations, represents the irregular and unpredictable components in a time series that do not follow a discernible pattern.

**Differencing:** Differencing is used to make the difference in values of a specified interval.

**Stationarity:** A stationary time series is one whose statistical properties, such as mean, variance, and autocorrelation, remain constant over time.

**Order:** The order of differencing refers to the number of times the time series data needs to be differenced to achieve stationarity.

**Autocorrelation:** Autocorrelation, is a statistical method used in time series analysis to quantify the degree of similarity between a time series and a lagged version of itself.

**Resampling:** Resampling is a technique in time series analysis that involves changing the frequency of the data observations to reveal patterns or trends more clearly.

# Importing the Libraries
All the libraries required for this project are as follows

*   Numpy
*   Pandas
*   Matplotlib

# Conclusion

Initially null hypothesis is accepted as the data does not appear to be stationary according to the Augmented Dickey-Fuller test. To achieve stationarity before applying time series models, **Differencing** is used to smoothen the Data.

After that ADF test is conducted again, where the ADF Statistic < all Critical Values. 
So,the null hypothesis is rejected.

The data appear to be stationary according to the Augmented Dickey-Fuller test.

This suggests that differencing is needed to achieve stationarity before applying time series models.
