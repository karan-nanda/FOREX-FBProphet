# FOREX-FBProphet

## Prepare your data:

 - Make sure you have a CSV file containing historical Forex data. The dataset used can be found [here](EURUSD_Candlestick_1_Hour_BID_04.05.2003-15.04.2023.csv)

## Customize the model parameters:


- **l**(Lowercase L): Index of the last candlestick used for training.
- **backcandles**: Number of previous candlesticks to include in the training data.
- **frontpredictions**: Number of future time steps to predict.
- **diff_limit**: Limit used for generating a signal.
- **signal**: Set to True to generate a signal, or False to return forecasted values.




## Disclaimer
- Trading in the Forex market involves substantial risk and may not be suitable for all investors. The provided model is for educational purposes only and should not be considered as financial advice.
