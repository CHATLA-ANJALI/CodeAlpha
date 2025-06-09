Sales Prediction using Python Project 

Overview
This project builds a machine learning model to predict sales based on advertising budgets spent on different platforms: TV, Radio, and Newspaper. Using historical sales data, the model learns how advertising spend influences sales and helps forecast future sales to optimize advertising strategies.

Project Components

1. Data Loading
Loads dataset from CSV using pandas.read_csv()

Checks for missing values and basic data integrity

2. Data Exploration
Inspects the dataset with .head(), .info(), and .describe()

Visualizes data relationships via pairplots and correlation heatmaps

3. Data Preprocessing
Selects relevant features (TV, Radio, Newspaper) as predictors

Sets Sales as the target variable

4. Model Training
Splits data into training and testing sets (train_test_split)

Uses LinearRegression model from scikit-learn to fit training data

5. Model Evaluation
Predicts on the test set

Calculates metrics: R² Score, Mean Squared Error

Visualizes actual vs predicted sales

6. Prediction
Allows users to input new advertising budgets

Outputs predicted sales based on the trained model

Dependencies:

pandas
numpy
matplotlib
seaborn
scikit-learn
