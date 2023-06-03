## LSTM-Project
This is an implementation of a Long Short-Term Memory (LSTM) model using PyTorch to predict the closing stock price of a particular stock. The model is trained on historical stock market data, and it learns to predict the closing price for the next day based on the previous day's data.
# Table of Content
  * Installation
  * Usage
  * Data
  * Model
  * Result
# Installation
To run this project, it is needed to install the following libraries:
 * Python 3
 * PyTorch
 * NumPy
 * Pandas
 * Plotly
 * yfinance
# Usage
In order to run the model, run the Stock-Market Prediction - LSTM.ipynb file with Jupyter Notebook or Jupyter Lab after installing the libraries.
``` python 
Stock-Market Prediction - LSTM.ipynb
```
# Data 
The stock market dataset used in this project is obtained from Yahoo Finance. The dataset contains daily stock prices and volumes for a particular stock, and it covers a period of several years. Historical stock market data is widely available from a variety of sources, including financial news websites, stock market data providers, and publicly available data from stock exchanges.

When using historical stock market data, it's important to ensure that the data is accurate and reliable. Some sources of historical stock market data may contain errors or inaccuracies, so it's important to carefully validate and clean the data before using it for analysis or machine learning.

# Model
The LSTM model used in this project consists of several LSTM layers followed by a dense output layer. The model is trained using a mean squared error (MSE) loss function and an Adam optimizer. The model is trained for a fixed number of epochs, and the learning rate is reduced if the validation loss does not improve for a certain number of epochs.
