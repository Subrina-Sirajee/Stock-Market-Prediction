# Stock Market Prediction Using Bidirectional LSTM

This project aims to predict stock market prices using a Bidirectional Long Short-Term Memory (LSTM) neural network. The model is trained on historical stock data and makes predictions for future stock prices.

## Overview

The project consists of the following components:

- Data Collection: Historical stock data is collected using the Yahoo Finance API.
- Data Preprocessing: The data is preprocessed, including scaling and splitting into training and test sets.
- Model Development: A Bidirectional LSTM model is developed using TensorFlow and Keras.
- Model Training: The model is trained on the training data with early stopping to prevent overfitting.
- Model Evaluation: The model's performance is evaluated using metrics such as Root Mean Squared Error (RMSE) on both training and test datasets.
- Prediction Visualization: Predicted stock prices are visualized along with the original data to assess the model's accuracy.

## Requirements

- Python 3.x
- TensorFlow
- Keras
- NumPy
- pandas
- yfinance
- scikit-learn
- matplotlib

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/Subrina-Sirajee/stock-market-prediction.git
