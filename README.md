# Stock_price_prediction
Stock Price Prediction using Machine Learning

This project predicts future stock closing prices based on historical data such as:

Opening Price

Closing Price

High & Low Prices

Trading Volume

I experimented with two different models:

Linear Regression → a simple baseline model

LSTM (Long Short-Term Memory) → a neural network designed for time-series forecasting
Project Workflow

Dataset: Stock market data (from Kaggle).

Preprocessing: Cleaned and scaled data for consistency.

Splitting Data:

Training data → older dates

Testing data → recent dates

Models Built:

Linear Regression → captures basic trend.

LSTM → learns patterns from past sequences.

Evaluation: Compared models using:

MAE (Mean Absolute Error)

RMSE (Root Mean Squared Error)



Results

Linear Regression: Good as a baseline.

LSTM: Performed better since it learns time dependencies.

Key Learning → ML can’t predict with 100% accuracy, but it helps reveal patterns and trends.
