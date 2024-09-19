# Home-Price-Prediction-Analysis

# Understanding the Problem:
We're tasked with predicting house prices using a dataset containing information like Address, Rooms, Type, Price, Seller, etc. Ridge and Lasso regression are suitable for this task due to their ability to handle multicollinearity and prevent overfitting, which are common issues in regression problems.

# Data Preprocessing Steps:
## Model Selection and Training:

Split Data:

Divide the dataset into training and testing sets.
Model Selection:

Choose between Ridge and Lasso regression based on the specific goals.
**Ridge Regression**: Suitable for preventing overfitting when there's multicollinearity.
Training Accuracy:66.2%
Testing Accuracy: 66.7%
**Lasso Regression**: Can perform feature selection by shrinking coefficients of less important features to zero.
Training Accuracy:67.6%
Testing Accuracy: 66.3%
