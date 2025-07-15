# 📈 Google Stock Price Prediction using Time Series Forecasting

This project applies deep learning techniques to predict Google’s stock price using historical data. The model is trained on a sequence of past stock prices using LSTM (Long Short-Term Memory) networks — a powerful class of Recurrent Neural Networks (RNNs) suitable for time-dependent data.

---

## 📁 Files Included

| File                             | Description                                   |
|----------------------------------|-----------------------------------------------|
| `Google_Stock_Price.csv`         | Historical stock prices for training.         |
| `Google_Stock_Price_Test.csv`    | Data used for testing model predictions.      |
| `Google Stock Price Prediction.ipynb` | Notebook with full data preprocessing, model building, and evaluation using LSTM. |

---

## 📌 Problem Statement

Forecasting stock prices is a challenging task due to the highly volatile nature of markets. This project aims to:
- Learn patterns from sequential price data
- Predict future closing prices based on historical data

---

## 🔧 Technologies Used

- Python
- Pandas, NumPy, Matplotlib
- TensorFlow / Keras
- Scikit-learn
- MinMaxScaler for normalization

---

## 🧠 Model Architecture

- Sequence windowing of stock price data
- LSTM layers with dropout for regularization
- Dense output layer for final prediction

---

## 📊 Workflow Summary

1. **Data Preprocessing**
   - Normalize using MinMaxScaler
   - Generate sequences for training (X) and target (y)

2. **Model Training**
   - Build and train an LSTM model
   - Monitor loss and optimize for best fit

3. **Evaluation**
   - Predict on test data
   - Compare predicted vs. actual stock prices using line plots

---

## 📈 Results

The LSTM model was able to learn the trend in the training data and showed reasonable performance in predicting stock movements on unseen data. Visualization helps highlight the trend-following nature of the prediction.

---

## 🚀 Future Improvements

- Use additional technical indicators (e.g., RSI, MACD)
- Incorporate news sentiment or volume data
- Try other architectures like GRU, BiLSTM
- Deploy the model as a real-time forecasting tool using Streamlit or Flask

---

## 👤 Author

**Tarun Virat**  
🔗 [LinkedIn](https://www.linkedin.com/in/tarunpeela29)  
💻 [GitHub](https://github.com/TarunVirat)

---

## 🏷️ Tags

`#TimeSeries` `#LSTM` `#StockPrediction` `#DeepLearning` `#Keras` `#GoogleStock`


