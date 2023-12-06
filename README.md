### Bull Market or Bear Market: Recession Time Series Prediction for Q1 2024

This project is a part of the ADS-506 course in the Applied Data Science Program at the University of San Diego.
### Project Status: [Planned, Active, On-hold, Completed]

### Installation
Project is developed with Python. 
Required machine: 


### Project Intro/Objective
The motivation for choosing this project is to use time series analysis to predict stock price movement. There are two invesment vehicles that were looked at SPY and AMZN. In order to perform the forecast, we use two approach: 
- Find a model to predict future stock price or stock price movement direction
- Find a model to predict what influences the stock price movement

The motivation for choosing this project is Financial markets and their subsequent investment vehicles present significant opportunity to manage risk and build capital. Through deeper understanding of the underlying characteristics of the markets and these vehicles, we may be able to leverage our growing knowledge of time series analysis to decompose price movements by price level, price trend, quarterly seasonality, and noise. Furthermore, understanding what may influence these components further aims to strengthen our ability to perform time series price prediction to manage risk and build capital.

### Partner(s)/Contributor(s)
 John Vincent Deniega
 Ravita Kartawinata
 Gabriella Rivera
https://github.com/vanguardfox/ADS506-F23

### Methods Used
A few examples are: 
 Stationary
 Simple Exponential
 Advance Exponential (Holt Winter)
 ARIMA
 Logistic Regression
 MLP

### Technologies
 Python

#### Problem Statement: Short Description of Your Time Series Project and Objective(s): 
In the fourth quarter of 2023, the US stock market is experiencing significant volatility. Objective is to analyze and understand the current environment across multiple dimensions in order to predict with sound data science principles where the US stock market will be by the end of the first quarter of 2024. Success criteria includes whether three-month prediction interval of S&P 500 was within +/-20% prediction error

#### Description of your selected dataset:
Dataset is live financial market data sourced from Yahoo Finance using the Python application programming interface, yfinance to pull/scrape live data. Interface is licensed under Apache Software License as of submission.

#### Data source, number of variables, size of dataset, etc: 
Data is sourced from Yahoo Finance with an extensive set of modules, attributes, and methods available to be utilized in Python. There are at least 14 callable methods with at least 20 attributes or original variables. Size of the dataset is not applicable due to the source consisting of live data.

#### Notable findings from your initial EDA:
Initial EDA findings include the time series of S&P500 ETF’s stock price exhibiting non-stationarity over the period of six months from May 2023 to November 2023 using the Augmented Dickey-Fuller test statistic method. Further transforming the time series with discrete differencing of one period reveals characteristics of a difference-stationary series using first order differenced analysis. Additional EDA on potential candidates such as broader market indices and interest rates as well as moving average smoothing techniques are planned for next-step analysis.



### License
You can add under what license your project is. As a good practice, add LICENSE file in your
project folder as well.
Acknowledgments
