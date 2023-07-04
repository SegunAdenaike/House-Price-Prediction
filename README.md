# House-Price-Prediction

## Data Understanding
The given dataset contains 10 features and 1 target variable, which is price. The features
are a mix of categorical and continuous variables, such as the number of rooms,
bathrooms, and kitchens, as well as binary variables indicating the presence of features
such as French doors, backyard, furnished rooms, green paint, solar power, wood floors,
QLM security, and a club access variable. The target variable, price, represents the price
of each property and ranges from 2235 to 15035.

## Model Building
The objective of this project is to build a model that can predict house prices based on
features provided in the dataset, which makes it a regression problem. For accurate
predictions, the dataset was trained using four algorithms. The algorithms are Linear
Regression, K Neighbor regression, Extreme Gradient Boost and Random Forest. The
best performing model was then selected based on the following performance metrics: RSquared (R2) score, mean squared error and mean absolute error.
The linear regression model performed the best, with R2 score of 0.99996, mean squared
error of 169, and mean absolute error of 13. The Linear Regression model was then
selected as the model of choice for predicting the housing prices.
Extreme Gradient Boost also performed very well in fitting the dataset, with R2 score of
0.9996, mean squared error of 1865.4, and mean absolute error of 33.8. Thisperformance was optimized by using grid search to find the best hyper parameters for the
model. The hyper parameters that were tuned are learning rate, maximum depth and
number of estimators.
