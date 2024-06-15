# Linear Regression for Restaurant Profit Prediction

## Overview

This project aims to build a linear regression model to predict the monthly profits of a restaurant franchise based on the population of the city where the restaurant is located. The model uses a dataset containing historical data of city populations and corresponding restaurant profits.

## Problem Statement

As the CEO of a restaurant franchise, determining the potential profitability of new locations is crucial for business expansion. By leveraging linear regression, we aim to provide insights into which cities might yield higher profits based on their population.

## Dataset

The dataset consists of:
- **x_train**: City populations (in units of 10,000)
- **y_train**: Monthly profits (in units of $10,000)

The dataset contains 97 training examples, where each example pairs a city’s population with the corresponding monthly profit (which can be negative to indicate losses).

## Implementation Steps

1. **Compute Cost Function**: Implement a cost function to measure the accuracy of the model’s predictions.
2. **Gradient Descent**: Implement gradient descent to optimize the model parameters (slope and intercept).
3. **Training the Model**: Use batch gradient descent to train the model on the training data.
4. **Visualize Results**: Plot the dataset and the linear regression line to visualize the model’s fit.
5. **Make Predictions**: Use the trained model to predict profits for new cities based on their populations.

## Usage

To run the project:
- Ensure Python 3.x is installed along with necessary libraries (`numpy`, `matplotlib`).
- Execute the provided Python scripts or Jupyter Notebook cells sequentially.

## Example Predictions

After training the model, example predictions can be made:
- For a city with 35,000 people, the predicted profit is $4519.77 (assuming a multiplier of 10,000).
- For a city with 70,000 people, the predicted profit is $45342.45.

## Conclusion

Linear regression provides a straightforward approach to predicting profits based on population size. The model’s accuracy can be further evaluated using metrics like mean squared error or R-squared.
