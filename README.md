# LSTM-Stock-Prediction
A mini group project that tries to utilize LSTM to predict Jakarta Stock Exchange Composite (JKSE) movement

The project tries to train an LSTM model to predict JKSE Open values from day to day. Basic data preprocessing was used such as MinMaxScaler along with 3 hidden LSTM layers. The resulting model seems to be overfit since it basically just mimics the previous day's data and could not accurately forecast the open movement.
