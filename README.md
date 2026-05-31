# Housing Price Prediction Using Machine Learning

## Project Overview

This project aims to predict housing prices using machine learning techniques. The dataset contains various housing characteristics such as crime rate, number of rooms, tax rate, and other factors that influence property values.

Advanced techniques such as Cross Validation, Hyperparameter Tuning, and SGD , Ridge , Lasso and Elastic Net Regression were applied to improve model performance and ensure reliable predictions.

## Objectives

- Analyze factors affecting housing prices.
- Perform exploratory data analysis (EDA).
- Detect and handle outliers.
- Train and evaluate regression models.
- Compare model performances and identify the best predictor.

## Dataset Features

The dataset includes variables such as:

- CRIM - per capita crime rate by town
- ZN - proportion of residential land zoned for lots over 25,000 sq. ft.
- INDUS - proportion of non-retail business acres per town.
- RIVER - River dummy variable (1 if tract bounds river; 0 otherwise)
- NOX - nitric oxides concentration (parts per 10 million)
- RM - average number of rooms per dwelling
- AGE - proportion of owner-occupied units built prior to 2000
- DIS - weighted distances to five employment centres
- RAD - index of accessibility to radial highways
- TAX - full-value property-tax rate per $10,000
- PTRATIO - pupil-teacher ratio by town
- LSTAT - % lower status of the population
- PRICE - Median value of owner-occupied homes in $1000's

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- StatsModels
- Jupyter Notebook
- Machine Learning Models

## Machine Learning Techniques Used

- Data Preprocessing and Feature Scaling
- Exploratory Data Analysis (EDA)
- Outlier Detection and Treatment
- Train-Test Split
- K-Fold Cross Validation
- Hyperparameter Tuning using GridSearchCV
- Model Building
- Model Evaluation and Comparison

## Machine Learning Models

The following regression models were implemented and evaluated:

- OLS Regression
- Linear Regression
- SGD Regression
- Ridge Regression
- Lasso Regression
- Elastic-Net Regression

## Evaluation Metrics

Model performance was assessed using:

- R² Score
- Mean Squared Error (MSE)

## Key Insights

- Housing prices are strongly influenced by factors such as  number of rooms and socio-economic features.
- RM had strong positive correlation with PRICE, indicating that houses with more rooms tend to have higher prices.
- LSTAT showed strong negative correlation with PRICE, indicating that higher lower-status population percentage reduces house prices.
- Certain feature like crime rate negatively impact property values.
- Feature scaling and preprocessing significantly improved model performance and prediction stability.
- Models like OLS Regression, Linear Regression, SGD Regression , Ridge Regression, Lasso Regression and Elastic Net Regression were able to capture price trends with reasonable accuracy.
- After applying cross-validation and hyperparameter tuning, model performance improved and reduced overfitting.
- The dataset shows that housing prices are not determined by a single factor but by a combination of multiple variables.

## Results

The models were compared based on evaluation metrics:

| Model              | Train set MSE   | Test set MSE  | R² Score |
|--------------------|-----------------|---------------|----------|
| OLS Regression     |      22.07      |      24.90    |  0.729   |
| Linear Regression  |      22.07      |      24.90    |  0.728   |
| SGD Regression     |      22.15      |      25.11    |  0.727   |
| Ridge Regression   |      22.07      |      24.94    |  0.728   |
| Lasso Regression   |      22.89      |      26.44    |  0.718   |
| Elastic Net        |      22.55      |      26.29    |  0.722   |

## Future Improvements

- Deployment as a web application

## Author

Sweta Agarwal

M.Sc. Statistics Student | Data Analytics & Machine Learning Enthusiast