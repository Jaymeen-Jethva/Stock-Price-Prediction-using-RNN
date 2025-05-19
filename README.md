# 📈 Stock Price Prediction Using RNNs

This project demonstrates how Recurrent Neural Networks (RNNs) can be used to predict the future stock prices of four major tech companies: **Amazon (AMZN), Google (GOOGL), IBM, and Microsoft (MSFT)**. Using historical data and sequential deep learning models like Simple RNNs, LSTMs, and GRUs, this notebook aims to forecast stock closing prices over time.

---

## 📌 Objective

The main objective is to use past stock data to predict future prices. By combining stock data from multiple companies in the same sector (Technology), the model captures broader market behavior to make better forecasts.

---

## 💡 Business Value

- Stock market data is inherently sequential, making it ideal for RNN-based deep learning models.
- Predicting stock prices accurately can lead to better financial decision-making and potentially higher returns.
- This approach can be a stepping stone toward building more complex financial forecasting systems.

---

## 📂 Data Description

The dataset includes daily stock market data from **2006 to 2018** for the four companies. Each file contains the following columns:

- `Date`
- `Open`
- `High`
- `Low`
- `Close`
- `Volume`
- `Name`

Each file has 3,019 records.

---

## ⚙️ Tech Stack

- **Languages**: Python
- **Libraries**: NumPy, Pandas, TensorFlow (Keras), Matplotlib, Seaborn, scikit-learn
- **Models Used**:
  - Simple RNN
  - LSTM
  - GRU
  - Bidirectional RNN
- **Optimization**:
  - Random Search for Hyperparameter Tuning
  - EarlyStopping Callback
