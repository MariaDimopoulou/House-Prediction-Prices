# House-Prediction-Prices

## Overview

This project aims to predict house prices based on various features such as the area of the house and the number of bedrooms. The implementation includes the use of linear regression models, train-test splitting, feature engineering, and cross-validation.
The project was part of a Data Anlysis course in my Master's program and is intended for educational purposes.

## Files and Directories

- **data/housedata1.xlsx**: Excel file containing the dataset used for the project.

## Project Structure

1. **Data Loading and Preprocessing:**
    - The project begins by loading the dataset from 'data/housedata1.xlsx'.
    - Features (e.g., house area and number of bedrooms) and the target variable (house prices) are extracted.

2. **Linear Regression Models:**
    - Two linear regression models are implemented:
        - `basic_model`: Trained on the entire dataset.
        - `model`: Trained on a random train-test split of the data.

3. **Model Evaluation:**
    - The performance of the models is assessed using Root Mean Squared Error (RMSE) on both training and test sets.

4. **Feature Engineering:**
    - Additional features are introduced based on conditions, contributing to a more complex model.

5. **Cross-Validation:**
    - A cross-validation function is implemented to assess the model's performance across different folds.

6. **Visualization:**
    - Scatter plots are created to visualize the relationship between actual and predicted house prices.
