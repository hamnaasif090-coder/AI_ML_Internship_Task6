# House Price Prediction

## Task Objective
The objective of this project is to predict house prices using key property features by training and evaluating regression models. The goal is to assess how well machine learning models can estimate housing prices and to analyze their performance using standard error metrics.

## Dataset Used
House Price Prediction Dataset (Kaggle), containing the following relevant features:
- Area
- Bedrooms
- Bathrooms
- Floors
- YearBuilt
- Condition
- Garage
- Location  
- Price (target variable)

## Models Applied
- Linear Regression (baseline)
- Gradient Boosting Regressor
- Tuned Gradient Boosting Regressor using GridSearchCV and cross-validation

## Key Results and Findings
- Baseline Gradient Boosting achieved an MAE of approximately 246,000 and RMSE of approximately 287,000.
- After hyperparameter tuning, the model achieved an MAE of approximately 243,000 and RMSE of approximately 280,000.
- Hyperparameter tuning using cross-validation slightly reduced prediction error, improving MAE from approximately 246k to 243k and RMSE from 287k to 280k. This indicates improved generalization; however, limited feature diversity restricts further accuracy gains.
- Further tuning was unlikely to yield significant gains due to limited feature information and diminishing returns, so a balanced and computationally efficient configuration was selected.
