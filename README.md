# House Price Prediction Project

This project uses a linear regression model to predict house prices based on features such as the number of bedrooms, bathrooms, living space area (sqft_living), and lot size (sqft_lot).

## Project Overview

The project involves the following steps:

1. **Data Loading and Exploration:**
   - The code loads a dataset of house sales data ('house data.csv').
   - It then performs exploratory data analysis, including displaying summary statistics and checking for missing values.
   - A pair plot is used to visualize the relationships between key features.

2. **Data Preprocessing:**
   - Missing values in numerical columns are handled by filling them with the mean of the respective columns.
   - The date column (if present) is converted to datetime objects for proper handling.

3. **Model Building and Training:**
   - The data is split into training and testing sets.
   - A linear regression model is created and trained on the training data.

4. **Model Evaluation:**
   - The model's performance is assessed using R-squared and Mean Squared Error (MSE) metrics on the test data.
   - Actual vs. predicted prices are visualized in a scatter plot.
   - A residual plot is generated to assess the model's assumptions.

5. **Prediction:**
   - The trained model is used to make predictions on new, unseen data.

## Dependencies

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Usage

1. Make sure you have the necessary dependencies installed.
2. Place your house sales data in a CSV file named 'house data.csv'.
3. Run the Python code provided in the notebook to train the model and make predictions.

## Results

The model's performance is summarized using R-squared and MSE. The scatter plot and residual plot provide visual insights into the model's accuracy and potential limitations.
