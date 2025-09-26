📈 Stock Price Prediction with LSTM (PyTorch)

This project implements a stock price prediction model using Long Short-Term Memory (LSTM) networks in PyTorch. It demonstrates how to preprocess time series stock data, train an LSTM model, and evaluate predictions against actual prices.

🚀 Features:

📊 Data Source: Historical stock data (e.g., NVDA) from Stooq or Yahoo Finance
🔧 Preprocessing:
- StandardScaler normalization
- Sliding window sequence creation
- Train/test split (80/20)

🤖 Model:
- Multi-layer LSTM built with torch.nn.LSTM
- Fully connected linear output layer

🎯 Training:
- Runs on CPU or GPU
- Mean Squared Error (MSE) loss
- Adam optimizer

📈 Evaluation:
- Inverse-transformed predictions (back to original scale)
- Side-by-side plots of actual vs predicted prices

Key packages:
- numpy
- pandas
- matplotlib
- scikit-learn
- torch
- pandas-datareader
