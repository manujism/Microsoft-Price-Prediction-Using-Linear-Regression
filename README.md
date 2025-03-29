# Microsoft-Price-Prediction-Using-Linear-Regression

This project is a time series analysis and linear regression modeling of Microsoft Corporation’s (MSFT) stock price over the last five years. It serves as a hands-on demonstration of using Python for financial data analysis, trend forecasting, and basic predictive modeling. The core goal is to analyze long-term price movement trends of MSFT stock and predict a simple linear trajectory using machine learning (Linear Regression). By fitting a regression line to the historical closing prices, we can visually and mathematically understand how the stock has performed over a multi-year horizon.

-------

Project Objectives
1. Fetch and prepare real-world stock data using yfinance.
2. Visualize raw and modeled stock price behavior.
3. Train a Linear Regression model to detect trends.
4. Predict and plot future-like price trends.
5. Measure model performance using standard regression error metrics.
6. Understand the mathematics and limitations behind the model.

   -----


Machine Learning Model Used : Linear Regression
Linear Regression is upervised learning algorithm that models the relationship between a dependent variable (stock price) and an independent variable (date). It tries to fit the best straight line through the data points.

The model uses the equation of a straight line: **Price = m * Date_ordinal + b**
Where:
m = Slope of the line (rate of price change)
b = Intercept (predicted price at starting point)
Date_ordinal = Numeric representation of the date (used as input)

The model finds the best-fitting line by minimizing the sum of squared errors between actual and predicted prices.

------







