# Univariate-time-series-forecasting
A single univariate time series is analyzed using five distinct prediction strategies, each competing against the others to determine the most effective forecaster.
Both, direct 60-day and rolling 1-day forecast horizons, are considered and evaluated.<br> 
<br>
ts1: facebook Prophet, perfect quick benchmark.<br>
ts2: Manually tuned, old-fashion SARIMA approach.<br>
ts3: Kats metalearning. Scalable time-series autoML.<br>
ts4: Prior to performing grid search on Sklearn algorithms, the time series data is tabularized.<br>
ts5: The autoregressive neural network approach based on PyTorch.
<br><br>
ts: Performance comparison (MAPE, RMSE, MAE).<br> 
Libraries employed: numpy, pandas, matplotlib, statsmodels, facebook Kats, sktime, sklearn, neuralprophet.<br>
<br>
Data source: https://www.kaggle.com/datasets/mukeshmanral/univariate-time-series
