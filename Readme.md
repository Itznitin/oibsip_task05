# Sales Prediction Project

## Project Overview
In this project, we build a sales prediction model using Python and machine learning. The goal of this project is to predict sales based on factors such as the amount spent on advertising the product, the segment of people advertised for, or the platform the advertisement is on.

## Dependencies
- Python
- pandas
- scikit-learn
- seaborn
- matplotlib

## Dataset
The dataset used in this project is named 'Advertising.csv'. It contains the following columns:
- 'TV': Advertising dollars spent on TV for a single product in a given market (in thousands of dollars).
- 'Radio': Advertising dollars spent on Radio.
- 'Newspaper': Advertising dollars spent on Newspaper.
- 'Sales': Sales of a single product in a given market (in thousands of widgets).

## Methodology
We use the Linear Regression algorithm for the machine learning model and create a new feature 'TotalSpend' which represents the total advertising spend across all channels (TV, Radio, Newspaper).

## Steps
1. **Import necessary libraries**: We import pandas for data manipulation, train_test_split for splitting the data, LinearRegression for the machine learning model, and seaborn and matplotlib for data visualization.
2. **Load the dataset**: We load the 'Advertising.csv' dataset using pandas.
3. **Perform exploratory data analysis**: We check the shape of the dataset, check for missing values, display summary statistics, display the correlation matrix, and create a pairplot.
4. **Feature Engineering**: We create a new feature 'TotalSpend' which represents the total advertising spend across all channels (TV, Radio, Newspaper).
5. **Split the dataset into features and target variable**: We split the 'TV', 'Radio', 'Newspaper', and 'TotalSpend' columns as our features and the 'Sales' column as our target variable.
6. **Split the dataset into training and testing sets**: We split the dataset into training and testing sets with a test size of 0.2.
7. **Train the model**: We create a Linear Regression model and train it using the training data.
8. **Make predictions and evaluate the model**: We make predictions on the testing set, print the coefficients of the model, compare actual output values with predicted values, and calculate the Mean Absolute Error, Mean Squared Error, and Root Mean Squared Error of the model.

## Results
The performance of the model is evaluated using three metrics: Mean Absolute Error, Mean Squared Error, and Root Mean Squared Error. The results are printed at the end of the notebook.
