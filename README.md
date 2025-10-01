# MRF stock price prediction

This project implements a machine learning-based stock price prediction system for MRF Ltd. (MRF.NS) using historical stock data from Quandl and Yahoo Finance (yfinance).

It includes two prediction approaches:

Classification (KNN Classifier): Predicts whether to Buy (+1) or Sell (-1) the stock.

Regression (KNN Regressor): Predicts the closing price of MRF stock.

🚀 Features

Fetches stock data from Quandl and Yahoo Finance

Preprocesses data by creating new features (Open-Close, High-Low)

Implements KNN Classification with GridSearchCV for hyperparameter tuning

Implements KNN Regression for closing price prediction

Evaluates model performance using accuracy score and predicted vs actual comparison

Visualizes stock price history with matplotlib
