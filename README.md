# Coca-Cola Stock Analysis

This repository contains a Python script for analysing the historical stock prices of Coca-Cola using various financial indicators and statistical methods. The analysis is performed using the `pandas`, `ta`, `matplotlib`, and `scikit-learn` libraries.

## Kindly click open the notebook.ipynb file to view the code and visualisations!

## Features

The script performs the following tasks:

1. **Data Import and Preprocessing**
   - Reads the Coca-Cola stock data from a CSV file.
   - Displays the first few rows of the dataset.
   - Provides a summary of the dataset and statistical information on numerical columns.
   - Converts the `Date` column to datetime format and checks for any parsing issues.
   - Sets the `Date` column as the index.

2. **Visualisation of Stock Data**
   - Plots the closing prices of Coca-Cola stock over time.

3. **Technical Indicators**
   - Calculates and plots the Simple Moving Averages (SMA) for 20 and 50 days.
   - Calculates and plots the Exponential Moving Average (EMA) for 20 days.
   - Computes Bollinger Bands and plots them along with the closing prices.
   - Adds the Relative Strength Index (RSI) to the dataset and plots it.
   - Computes and plots the Moving Average Convergence Divergence (MACD) and its signal line.

4. **Data Cleaning**
   - Removes rows with missing values in critical columns.

5. **Linear Regression Modelling**
   - Defines the features (`X`) and the target variable (`y`) for a linear regression model.
   - Splits the data into training and test sets.
   - Fits a linear regression model to predict closing prices.
   - Evaluates the model by calculating the Mean Squared Error (MSE) on the test set.

## Requirements

To run the script, you need the following Python libraries installed:

- `pandas`
- `ta` (Technical Analysis library)
- `matplotlib`
- `seaborn`
- `scikit-learn`

You can install the required packages using the following command:

```bash
pip install pandas ta matplotlib seaborn scikit-learn


Usage
Clone this repository to your local machine.
Place the Coca-Cola_stock_history.csv file in the same directory as the script.
Replace the file_path variable with the actual path to your CSV file in the script.
Run the script to perform the analysis.
Output
The script will output:

Various plots displaying the Coca-Cola stock prices and technical indicators.
A cleaned dataset after removing rows with missing values.
The Mean Squared Error (MSE) of the linear regression model on the test data.
Notes
The dataset used for analysis is historical data and should be treated as such. This analysis is for educational purposes and does not constitute financial advice.
Ensure that the path_to_csv variable in the script points to the correct location of your CSV file.


Contributing
Contributions are welcome! Please feel free to submit a Pull Request or raise an Issue if you encounter any problems or have suggestions for improvement.


This README provides an overview of the project, instructions for setting it up, and details about its functionality.

