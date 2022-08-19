# Predicting Car Prices using sklearn
## by Carol Obura

**Introduction**

Using sklearn, pandas, numpy and other python tools to predict various cars' market prices based their attributes such as weight of the car, acceleration speed, miles per gallon, among others.

The automobile dataset used is from the UCI Machine Learning Repository, and some of the features are:

1. Make of the car
2. Fuel type
3. Number of doors the car has
4. Body style; convertible, hatchback, etc
5. Actual price of the car

To predict the car prices, the following steps were taken:
- Data Cleaning, involving handling missing values and non-numeric columns
- Building univariate predictive model using holdout validation and K-Fold cross validation methods
- Bulding multivariate model
- Hyperparameter optimization to tweak and improve the models
- Visual representation of the error metrics from the models

## Summary of findings
As we progress with the model building from univariate through to the multivariate model, adding more features in the model gives better predictions, with minimal root mean squared error(rmse).

From the univariate model, engine size of a car is the predictor for car price, with an rmse of 3167.

From the multivariate model, using four features, that is engine size, city mpg, horsepower and highway mpg are the best predictors with rmse of 2830. These features are finally used to get predicted car prices from the dataset's records.
