# Home-Price-Prediction-Analysis

 Understanding the Problem:
I am tasked with predicting house prices based on a dataset containing information like Address, Rooms, Type, Price, Seller, etc. Before making predictions, I preprocessed the data to handle irregularities and implemented various techniques to improve prediction accuracy. 

# Data Preprocessing Steps:
 Model Selection and Training:

Split Data:
Divided the dataset into training and testing sets.

# Model Selection:
Linear Regression:
A baseline model to establish a benchmark.
Training score:68.2%
Testing Score: 13.8%

# Regularization
The regularization techniques are used to address the problem of overfitting. Overfitting occurs when a model becomes too complex, fitting the training data too closely but failing to generalize well to new, unseen data.
Choose between Ridge and Lasso regression based on the specific goals.

**Ridge Regression**: Suitable for preventing overfitting when there's multicollinearity.
Training Accuracy:66.2%
Testing Accuracy: 66.7%

**Lasso Regression**: Can perform feature selection by shrinking coefficients of less important features to zero.
Training Accuracy:67.6%
Testing Accuracy: 66.3%
