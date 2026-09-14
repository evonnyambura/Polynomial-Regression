# House Prices Prediction

A machine learning project that uses **Polynomial Linear Regression** to predict house prices using House Prices dataset.

## How it Works
1. **Loads the Data:** Combines the train and test data for clean preprocessing.
2. **Fills Missing Values:** Fills missing text with 'None' and missing numbers with the column median.
3. **Encodes Text:** Converts text categories into numbers using dummy variables.
4. **Feature Engineering:** Creates 2nd-degree polynomial features for key metrics like Quality and Area.
5. **Trains Model:** Standardizes the data and trains a Linear Regression model.
6. **Saves Predictions:** Exports the final results to a `submission.csv` file.

## Requirements
* Python 3
* pandas
* numpy
* scikit-learn
