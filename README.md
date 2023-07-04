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

## Feature Importance
The feature importance for the linear regression model was computed by multiplying the
regression coefficient of each feature by its standard deviation. It was necessary to do
this because the regression coefficient of the features alone will not accurately tell the
strength of each feature, as they do not have the same unit of measurement. The
importance of the features was then normalized to range from 0 to 100.

![Feature Importance](https://github.com/SegunAdenaike/House-Price-Prediction/assets/96291623/8507bc85-a0bf-424d-9d08-b980970a7d3f)

The importance of each feature is presented in the bar chart above. It can be seen that
the most important feature is room, with a normalized importance value of 100. This
means that this feature has the greatest influence on the model’s prediction compared to
the other features in the dataset, and removing or changing this feature could have a
significant impact on the accuracy of the model’s predictions.
The second most important feature is furnished, with a normalized importance value of
70.2 This feature is also highly influential, and removing or changing it could have a
significant impact on the model’s performance.

Normalized ImportanceOther features that are highly important include woodfloor, with a normalized importance
value of 66.3, solar_power with a normalized importance value of 53.7, club_access with
a normalized importance value of 25.6, and backyard with a normalized importance value
of 19.7.
