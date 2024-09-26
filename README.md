# Stock-Price-Prediction-And-Forecasting-Using-Stacked-LSTM
This project focuses on predicting stock prices using Stacked Long Short-Term Memory (LSTM) networks, a deep learning model that excels at time-series forecasting. LSTMs are particularly suited for stock market prediction due to their ability to retain information over long sequences, making them effective for modeling historical price trends.

Key Steps:
+ **Data Preprocessing:**
  Collected historical stock price data, including features like open, close, high, low prices, and trading volume.
  Handled missing data and normalized the dataset for consistent input to the model.
  Split the data into training and test sets to evaluate the model's performance.
  
+ **Model Development:**
  Designed a stacked LSTM model with multiple LSTM layers to capture complex temporal patterns.
  Implemented regularization techniques such as dropout to prevent overfitting.
  Fine-tuned hyperparameters, including the number of LSTM layers, units, learning rate, and batch size.

+ **Training the Model:**
  Used historical stock price data as input and trained the model using the Mean Squared Error (MSE) loss function.
  Optimized the model using the Adam optimizer, ensuring efficient training.
  
+ **Prediction and Evaluation:**
  Generated stock price predictions and compared them with actual prices using metrics like Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).
  Evaluated the model's ability to predict future stock prices over varying time horizons.
  
+ **Results:**
  The Stacked LSTM model achieved reliable accuracy in forecasting stock prices, effectively capturing trends and patterns in historical data.
  Visualized the predicted vs. actual stock prices to demonstrate the model's predictive capability.
  This project showcases how deep learning models like Stacked LSTM can be used for financial market forecasting, offering insights for investors and traders by predicting future stock price movements.
