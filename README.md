# Loan Repayment Prediction using Random Forest

## Overview of the Problem

In order to address the problem of predicting the risk of a borrower being unable to repay a loan, we will be using a machine learning algorithm called random forest. Random forest is an ensemble learning method that involves constructing multiple decision trees and combining their predictions to make a final prediction.

## Data Exploration

Before building and training the machine learning model, we need to load and explore the dataset. This step helps us gain a better understanding of the data, identify any issues or biases, and find relevant patterns or trends. It also allows us to ensure that the data is properly formatted and ready for analysis.

## Data Visualization

Data visualization helps us visualize the relationships between different variables and gain insights into the data. In this project, we use various plots and charts to explore the dataset, such as histograms, count plots, joint plots, and heatmaps. These visualizations help us understand the distribution of features, the relationship between variables, and the impact on loan repayment.

## Data Processing

Before training the machine learning model, we need to preprocess the data. In this case, we convert categorical variables into numerical form using one-hot encoding. This process creates dummy variables for each category, which are then used as features for the model. The target variable, "not.fully.paid," is separated from the input features.

## Decision Tree

To start with, we build a decision tree classifier using the `DecisionTreeClassifier` class from the `sklearn` library. The decision tree is trained on the training data using the `fit()` method. After training, we make predictions on the test data using the `predict()` method.

## Visualizing the Decision Tree

To understand the decision tree, we visualize it using the `plot_tree` function from `sklearn.tree`. This plot shows the structure of the decision tree, including the splits and leaf nodes. By following the splits and conditions, we can understand how the model makes predictions.

## Evaluation Metrics

We evaluate the performance of the model using classification metrics such as precision, recall, and F1-score. The `classification_report()` function provides a summary of these metrics. Additionally, we use the `confusion_matrix()` function to get the confusion matrix, which shows the number of true positives, true negatives, false positives, and false negatives.

