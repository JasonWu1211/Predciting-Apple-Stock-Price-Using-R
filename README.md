# Time Series Analysis: Apple Stock Price | R

The motivation of our study is to analyze the trend in financial data. For this purpose, we collect our data from the daily historical Apple stock prices (open, high, low, close, and adjusted prices) from February 1, 2002 to January 31, 2017 extracted from the Yahoo Finance website.
[The data](day.csv) has logged the prices of the Apple stock every day and comprises of the open, close, low, high and the adjusted close prices of the stock for the span of 15 years. The goal of the project is to discover an interesting trend in the apple stock prices over the past 15 years (3775 attributes) and to design and develop the best model for forecasting.

![Forecast](/image/Screen%20Shot%202018-07-19%20at%203.35.14%20PM.png)

* ARMA(0,0) - EGARCH(1,1) model with t distribution - Most Adequate for forecasting the mean and volatility of the Apple stock price
* Captured the asymmetric volatility behavior of Apple stock return
* Negative shock have larger impact on the Apple stock return volatility than positive shock

[R code](/apple%20stock%20price%20prediction.R)
