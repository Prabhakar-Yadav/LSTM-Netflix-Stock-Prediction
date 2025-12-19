LSTM-Based Stock Price Prediction
Project Overview

This project focuses on predicting stock prices using a Long Short-Term Memory (LSTM) neural network, which is well-suited for time-series and sequential data. The model is trained on historical stock market data to learn temporal patterns and predict future closing prices.

This project was completed as part of the WiDS Final Assignment.

Problem Statement

To build a deep learning model that predicts the next day’s stock closing price using historical price data and past trends.

Dataset

Source: Yahoo Finance API

Features: Open, High, Low, Close, Volume

Target Variable: Closing Price

Train-Test Split: 80% training, 20% testing

Methodology

Data cleaning and handling missing values

Feature selection focusing on closing prices

Data normalization using Min-Max scaling

Sequence generation using a 60-day rolling window

LSTM model training and evaluation

Model Architecture

LSTM layer (50 units) with dropout

LSTM layer (50 units) with dropout

Dense layer (25 units)

Output layer (1 unit)

Loss Function: Mean Squared Error

Optimizer: Adam

Results

The model captured overall stock price trends effectively

Performance Metrics:

MAE: 14.74

MSE: 313.66

RMSE: 17.71

The model showed limitations during sudden market fluctuations, highlighting the volatility of financial data

Tech Stack

Python

NumPy, Pandas

Matplotlib, Seaborn

TensorFlow / Keras

Jupyter Notebook
