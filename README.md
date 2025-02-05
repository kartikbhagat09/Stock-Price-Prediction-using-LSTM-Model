# Stock-Price-Prediction-using-LSTM-Model
Here, we use the LSTM model to train and predict stock prices.

Steps to Train an LSTM Model for Stock Price Prediction:

1. Preprocessing:

->Convert Date to datetime and set it as an index.
->Normalize numerical columns for better training.
->Decide whether to predict Close or Adj Close prices.

2. Prepare Data for LSTM:

->Create sequences (e.g., use the last 60 days to predict the next day).
->Reshape the data into (samples, timesteps, features).

3. Build and Train LSTM Model:

->Use TensorFlow/Keras to create an LSTM network.
->Train it using historical data and evaluate performance.

4. Prediction and Evaluation:

->Use test data to make predictions.
->Compare predictions with actual values using metrics like RMSE.
