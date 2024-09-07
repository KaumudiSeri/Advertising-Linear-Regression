# Car Advertising: Predicting Futuristic Sales
<br>

## Project Overview
<br>
This project aims to develop a machine learning regression model that predicts future car sales based on current advertising spends across various media channels. By leveraging historical data, the model will provide insights into how future sales are impacted by advertising efforts, enabling businesses to optimize their marketing budgets.
<br>

## Problem Statement
<br>
In the automotive industry, sales are directly influenced by advertising efforts across multiple mediums like TV, radio, and newspapers. The goal of this project is to:


* Predict future car sales using current advertising expenditures.
* Build a regression model to forecast sales based on advertising data.
* Evaluate the model's performance using error metrics such as Mean Squared Error (MSE) and Mean Absolute Error (MAE).
<br>

## Dataset
<br>
The dataset used for this project is advertising.csv, which contains the following columns:


* TV: Amount spent on TV advertising.
* Radio: Amount spent on radio advertising.
* Newspaper: Amount spent on newspaper advertising.
* Sales: The corresponding car sales.
<br>
The dataset provides the current advertising spends and the corresponding sales, which will be used to predict future sales.
<br>

## Approach

* Data Loading:
     * Download the advertising dataset and load it into the Python environment (e.g., Jupyter Notebook).

* Data Exploration:
     * Store the dataset as a Pandas DataFrame.
     * Perform basic exploratory data analysis (EDA) to understand central tendencies, dispersion, and data distribution.

* Data Preprocessing:
     * Handle missing and null values.
     * Treat any outliers that may distort the model’s predictions.

* Data Visualization:
     * Perform univariate and bivariate analysis to understand trends and patterns.
     * Use visualizations to explore relationships between the advertising mediums and sales.

* Correlation Analysis:
     * Identify correlations between features and the target variable (sales).

* Feature Selection & Data Split:
     * Split the dataset into X (features: TV, Radio, Newspaper) and Y (target: Sales) to prepare the data for model training.

* Model Building:
     * Train the data using a Linear Regression model or any suitable regression model.
     * Perform appropriate train-test splitting to ensure the model generalizes well.
 
* Prediction:
     * Use the trained model to predict future sales based on the test data (X-test).

* Model Evaluation:
     * Compare the predicted sales (Y_pred) with the actual test sales (Y_test).
     * Calculate performance metrics such as Mean Squared Error (MSE) and Mean Absolute Error (MAE).
     * The model with the lowest error is considered the best-performing model.
<br>

## Tools & Technologies

* Programming Language: Python 3.x
* Environment: Jupyter Notebook or any other Python-based IDE
* Libraries:
     * pandas for data manipulation.
     * numpy for numerical computations.
     * matplotlib and seaborn for data visualization.
     * scikit-learn for regression modeling and model evaluation.
<br>

## Expected Output
<br>

* A regression model that can predict future car sales based on current advertising expenditures.
* Model performance evaluated using error metrics like MSE and MAE to ensure the accuracy and reliability of the predictions.
<br>

## Conclusion
<br>
This project provides a framework for predicting future sales based on advertising data. By analyzing the relationship between advertising spend across various mediums and car sales, businesses can optimize their marketing strategies to drive better results. The regression model built can further be enhanced with hyperparameter tuning, more complex models, or advanced feature engineering.
