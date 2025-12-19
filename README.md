# LSTM-Based Stock Price Prediction

## Project Overview
This project focuses on predicting stock prices using a Long Short-Term Memory (LSTM) neural network. LSTM models are well suited for time-series data and are capable of learning long-term dependencies from historical stock prices.

This project was developed as part of the WiDS Final Assignment.

## Problem Statement
To build a deep learning model that predicts the next day’s stock closing price using historical market data and past price trends.

## Dataset
- Source: Yahoo Finance API  
- Features: Open, High, Low, Close, Volume  
- Target Variable: Closing Price  
- Train-Test Split: 80% training, 20% testing  

## Methodology
- Data cleaning and missing value handling  
- Feature selection focused on closing prices  
- Min-Max normalization  
- Sequence creation using a 60-day rolling window  
- Training an LSTM-based neural network  

## Model Architecture
- LSTM layer with 50 units and dropout  
- Second LSTM layer with 50 units and dropout  
- Dense layer with 25 units  
- Output layer with 1 unit  
- Loss Function: Mean Squared Error  
- Optimizer: Adam  

## Results
- The model successfully captured overall stock price trends  
- Performance Metrics:
  - MAE: 14.74  
  - MSE: 313.66  
  - RMSE: 17.71  
- The model struggled with sudden price fluctuations due to market volatility  

## Tech Stack
- Python  
- NumPy, Pandas  
- Matplotlib, Seaborn  
- TensorFlow / Keras  
- Jupyter Notebook  

Jupyter Notebook
