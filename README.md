House Price Prediction
This project focuses on predicting house prices using the Seattle House Dataset. 
The dataset includes detailed information about houses, such as location, size, and features, to build accurate regression models to estimate house prices.

Models and Performance
Several regression models were implemented and evaluated to determine their effectiveness:
Baseline Models:
Linear Regression
Lasso Regression
Ridge Regression
These models provided a solid starting point, with slight improvements in performance observed in Lasso and Ridge Regression due to regularization.
However, their ability to capture complex patterns in the data was limited.

Advanced Models:
Gradient Boosting
LightGBM
Neural Networks
Random Forest
These models excelled at capturing non-linear relationships in the data, significantly outperforming the baseline models. 
Among these, LightGBM emerged as the best-performing model, achieving the highest test accuracy and demonstrating strong generalization.
