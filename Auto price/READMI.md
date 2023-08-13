# Determining the car price

### Task:

The used cars sale service is developing an application to attract new customers. In it, you can quickly find out the market value of your car. Based on historical data, it is necessary to build a model to determine the cost of the car.

### Research steps:

1. Reserch and preprocessing of data.
2. Preparation of samples for training models using the OHE and OE methods.
3. 5 models training: LinearRegression, RandomForestRegressor, DecisionTreeRegressor, CatBoostRegressor, LGBMRegressor. Picked the best settings.
4. Analyze training time, prediction time and model quality.
5. Choose best model taking into account the training time and prediction, as well as the RMSE value.

### Conclusion:

We found out best model taking into account the training time and prediction, as well as the RMSE value.

According to the results of the rating, with a decrease in the weight of time by 90%, CatBoostRegressor model wins. We tested it on a test sample.

Prediction time 140 ms

RMSE 1510.3099651693
