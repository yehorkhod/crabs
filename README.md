# Predicting Crabs' Age

This project aims to predict the age of crabs based on various features such as
sex, length, weight and other characteristics.
The prediction is performed using machine learning models, specifically Ridge Regression and XGBRegressor.
The process involves reading and preprocessing the data, performing exploratory data analysis (EDA),
encoding categorical variables, scaling the data, and tuning model parameters to achieve the best performance.

Data was found here: `https://www.kaggle.com/datasets/sidhus/crab-age-prediction`

![plot](Crab.jpg)

## Results

Ridge:

    Mean Absolute Error: 1.61
    Mean Squared Error: 5.14
    Root Mean Squared Error: 2.27

XGBRegressor:

    Mean Absolute Error: 1.53
    Mean Squared Error: 4.89
    Root Mean Squared Error: 2.21
