# Forecasting the number of taxi orders for the next hour

### Task:

The taxi company has collected historical data on taxi orders at airports. To attract more drivers during peak load, they need to predict the number of taxi orders for the next hour.

### Research steps:

1. Reserch and preprocessing of data, resampling by one hour.
2. Preparation of samples for training models.
3. 4 models training: LinearRegression, Ridge, CatBoostRegressor, LGBMRegressor. Picked the best settings.
4. Choose best model taking into account the training time and prediction, as well as the RMSE value.

### Conclusion:

The value of the RMSE metric on the test sample should be no more than 48.

The best one turned out to be\
LGBMRegressor\
RMSE = 39.434187
