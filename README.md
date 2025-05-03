# Microsoft-Price-Prediction-Using-Linear-Regression

This project is a time series analysis and linear regression modeling of Microsoft Corporation’s (MSFT) stock price over the last five years. It serves as a hands-on demonstration of using Python for financial data analysis, trend forecasting, and basic predictive modeling. The core goal is to analyze long-term price movement trends of MSFT stock and predict a simple linear trajectory using machine learning (Linear Regression). 
By fitting a regression line to the historical closing prices, we can visually and mathematically understand how the stock has performed over a multi-year horizon.


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

The model uses the equation of a straight line: **Price = (slope) * Date_ordinal + (intercept)**
Where:

The model finds the best-fitting line by minimizing the sum of squared errors between actual and predicted prices.

------

Libraries Used

pandas - For data manipulation and preprocessing

numpy - For numerical computations

matplotlib - For data visualization

yfinance - For fetching stock data

sklearn.linear_model - For implementing linear regression

sklearn.metrics - For evaluating model performance


----

Implementation Steps

1. Download Data: Fetches MSFT stock price data from Yahoo Finance for the past 5 years.

2. Preprocess Data: Extracts only the closing price and drops missing values.

3. Convert Date to Ordinal: Converts dates to ordinal format to use them as a numerical feature.

4. Train Linear Regression Model: Fits a simple linear regression model to predict stock prices based on ordinal dates.

5. Make Predictions: Uses the trained model to predict stock prices.

6. Evaluate Model Performance: Calculates metrics such as R-squared, Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE).

7. Visualizations:

    Plots actual vs. predicted prices.

    Residual plot to analyze errors.

    Histogram of residuals to assess error distribution.

    Scatter plot of actual vs. predicted prices.


-----


Model Performance Metrics

The performance of the linear regression model is assessed using the following metrics:

1. R-squared: Measures the proportion of variance in the target variable explained by the model.

2. Mean Absolute Error (MAE): Average absolute difference between actual and predicted values.

3. Mean Squared Error (MSE): Average squared difference between actual and predicted values.

4. Root Mean Squared Error (RMSE): Square root of MSE, representing error magnitude.


------

Limitations

Linear Assumption: Stock prices do not always follow a linear trend.

Ignoring Market Factors: The model does not account for external factors like earnings reports, economic conditions, or investor sentiment.

Over-simplification: Stock prices are influenced by numerous unpredictable factors beyond historical trends.




