# Gold concentration forecast

### Task:

It is necessary to build a machine learning model for an industrial company. The model should predict the recovery coefficient of gold from gold-bearing ore based on data with extraction and purification parameters. The model will help to optimize production so as not to launch an enterprise with unprofitable characteristics.

### Research steps:

1. Reserch and preprocessing of data.
2. Preparation of samples for training models.
3. 3 models training: DecisionTreeRegressor, RandomForestRegressor, LinearRegression. Picked the best settings.
4. Selection of the best parameters and quality assessment using validation and sMape metrics for the Rougher and Final stages.

### Conclusion:
Best Model and Parameters for Rougher Stage:

Random forest\
depth=4\
estimators = 41

Best Model and Parameters for Final Stage:\
Random forest\
depth = 2\
estimators=6\
rougher sMAPE on training set 6.353403313266012\
final sMAPE on training set 8.642113350678812\
total sMAPE on training set 8.069935841325613\
rougher sMAPE on test sample 4.047971152088125\
final sMAPE on test set 8.530416432843461\
total sMAPE on test set 7.409805112654627
