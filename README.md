# Google Stock Price Prediction

Predict Google (GOOG) stock prices using SimpleRNN and LSTM networks in TensorFlow/Keras.  
Includes automated hyperparameter tuning with Keras Tuner, early stopping, and visualization of actual vs predicted prices.

---

## 🛠 Features
- Time-series forecasting for Google stock prices
- SimpleRNN and LSTM models
- Automated hyperparameter optimization with Keras Tuner
- Preprocessing of stock data from Yahoo Finance
- Validation set evaluation and MAE calculation
- Visualization of predictions vs actual prices

---

## 📂 Project Structure

```
google-stock-prediction/
 ├── google_stock_rnn_lstm.ipynb  # Jupyter Notebook
 ├── google_stock_rnn_lstm.py     # Python script
 ├── README.md
 ├── requirements.txt
 └── data/                        # optional: saved CSV data
```

---

## ⚡ How to Run

1. Create a virtual environment and activate it.
2. Install dependencies with `pip install -r requirements.txt`.
3. Run the script or Notebook to download data, train models, and visualize results.

---

## 🧰 Requirements

- Python 3.8+  
- numpy, pandas, matplotlib, scikit-learn  
- tensorflow, keras-tuner  
- yfinance==0.2.61  

---

## 📄 License

MIT License
