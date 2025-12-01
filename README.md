This project is a machine learning–powered stock price prediction web application built using TensorFlow LSTM, Flask, and a custom frontend UI for displaying predicted trends and price movements. The model is trained on historical stock data and uses a sequence-based LSTM architecture to predict next-day closing prices and generate Buy / Hold / Sell insights based on predicted market movement.
🚀 Features

📊 LSTM-based Stock Price Prediction

📈 Interactive Charts (using Charts.js)

🔍 Technical Indicators (SMA, EMA, returns)

🔮 Buy / Hold / Sell Signal Generator

🌐 Full-stack Web App (Flask API + HTML/CSS/JS frontend)

⚙️ Model trained and saved for instant inference

📦 Clean, modular backend (utils, model loader, preprocessing)

Tech Stack

Machine Learning

TensorFlow / Keras
LSTM Neural Network
Scikit-learn
Pandas, NumPy

Backend

Flask
Gunicorn
Python 3.x

Frontend

HTML
CSS
JavaScript
Charts.js


How It Works :

User enters a stock ticker (example: AAPL, TSLA, INFY).

Application fetches historical stock data through yfinance.

Data is preprocessed using:

MinMax Scaling

Sequence Windowing

SMA/EMA

LSTM model predicts the next-day closing price.

Backend generates a trend signal → Buy, Hold, or Sell.

Results are displayed with dynamic charts on the UI.