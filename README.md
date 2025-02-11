Here’s a complete Transformer-Based Stock Prediction pipeline using Hugging Face's Time Series Transformer and scikit-learn pipelines. This code:
✅ Loads stock data (from Yahoo Finance)
✅ Preprocesses and scales the data
✅ Trains a Transformer model for time series forecasting
✅ Evaluates the performance
This script fetches stock data, processes it into sequences, trains a Transformer model, and saves it.

 Dataset contains stock price data for HDFC with columns like Open, High, Low, Close, VWAP, Volume, and Turnover.
 I'll modify the code to use this dataset, focusing on the Close price for stock prediction.
✅ Make predictions on test data
✅ Inverse transform the scaled predictions
✅ Plot actual vs. predicted prices using Matplotlib

added code to plot actual vs. predicted stock prices using Matplotlib. Run the script, and you should see a graph comparing the predicted prices to real stock values.
