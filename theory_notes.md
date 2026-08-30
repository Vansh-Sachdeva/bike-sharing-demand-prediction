# Theory Notes — Linear Regression

## Simple Linear Regression
Equation: y = b0 + b1*x
- b0 = intercept
- b1 = slope

## OLSE (Ordinary Least Squares Estimation)
Closed-form solution: coefficients calculated directly using matrix formula,
no iteration needed. Fast and exact for smaller datasets.

## Gradient Descent
Iterative method to minimize cost function (Mean Squared Error) by updating
coefficients step-by-step in the direction that reduces error.
Cost function: MSE = (1/n) * sum((actual - predicted)^2)
Update rule: b = b - learning_rate * gradient

## Evaluation Metrics
- MAE (Mean Absolute Error): average of absolute errors
- MSE (Mean Squared Error): average of squared errors
- RMSE (Root Mean Squared Error): square root of MSE
- R2 Score: how much variance in target is explained by the model (closer to 1 = better)

## References
- UCI Machine Learning Repository — Bike Sharing Dataset
- scikit-learn documentation (LinearRegression, metrics)
- Class notes / lecture slides on Linear Regression
