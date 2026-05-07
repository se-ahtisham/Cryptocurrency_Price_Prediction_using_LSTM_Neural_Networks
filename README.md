# Cryptocurrency Price Prediction using LSTM Neural Networks
A deep learning project that predicts future Bitcoin closing prices using an LSTM (Long Short-Term Memory) neural network trained on historical cryptocurrency market data.

---

## 📌 Problem Statement

Cryptocurrency markets are highly volatile and difficult to predict using traditional methods. Traders and investors often struggle to identify future market trends from large amounts of historical price data.

This project solves this problem by using an **LSTM-based deep learning model** that learns patterns from previous Bitcoin prices and predicts future closing prices.

The system helps in:

* Understanding cryptocurrency price trends
* Learning time series forecasting with deep learning
* Predicting future Bitcoin prices from historical data
* Building AI-based financial prediction systems

---

## 🚀 Project Features

* Downloads real cryptocurrency data directly from Kaggle
* Cleans and preprocesses historical Bitcoin data
* Uses MinMaxScaler for feature normalization
* Creates sliding window sequences for time series learning
* Builds an LSTM neural network using TensorFlow/Keras
* Predicts future Bitcoin closing prices
* Evaluates performance using RMSE
* Visualizes Actual vs Predicted prices using graphs

---

## 🛠 Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* KaggleHub
* Jupyter Notebook

---

## 📂 Dataset

Dataset used:

* Historical Cryptocurrency Price Dataset from Kaggle
* Bitcoin historical market data

Dataset source:

* [https://www.kaggle.com/datasets/sudalairajkumar/cryptocurrencypricehistory](https://www.kaggle.com/datasets/sudalairajkumar/cryptocurrencypricehistory)

The project automatically downloads the dataset using `kagglehub`.

---

## 🧠 Machine Learning Workflow

### 1. Data Collection

* Downloads Bitcoin historical data from Kaggle

### 2. Data Cleaning

* Removes missing values
* Converts price values into numeric format

### 3. Feature Scaling

* Uses `MinMaxScaler` to normalize values between 0 and 1

### 4. Sequence Creation

* Uses a 50-day sliding window approach
* Previous 50 days → predict next day price

### 5. Model Building

* Builds an LSTM neural network using TensorFlow/Keras

### 6. Training

* Trains the model on historical Bitcoin prices

### 7. Prediction

* Predicts future closing prices

### 8. Evaluation

* Calculates RMSE (Root Mean Squared Error)
* Compares actual vs predicted prices

---

## 📈 Model Architecture

The model uses:

* LSTM Layer
* Dense Output Layer

Why LSTM?

* LSTM networks are designed for sequential and time-series data
* They can remember previous patterns over long periods
* Commonly used in stock market and cryptocurrency forecasting

---

## 📊 Output

The project generates:

* Predicted Bitcoin prices
* Actual vs Predicted price graph
* RMSE evaluation score
