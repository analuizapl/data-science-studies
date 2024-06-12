## Breast Cancer Diagnosis with Decision Tree Classifier

# Overview
This project utilizes a decision tree classifier to predict breast cancer diagnosis based on various features from the Breast Cancer dataset. The process includes data preprocessing, training the decision tree model, evaluating its performance using metrics like accuracy, and visualizing the decision tree structure.

# What is a Decision Tree?
A decision tree is a supervised machine learning model used for both classification and regression tasks. It works by recursively splitting the dataset into subsets based on the most significant feature at each node. The goal is to create a tree-like structure where each internal node represents a feature, each branch represents a decision rule, and each leaf node represents the outcome (class label for classification or predicted value for regression).

Decision trees are advantageous because they are easy to interpret and visualize. However, they can be prone to overfitting complex datasets.

# Confusion Matrix:
A confusion matrix is a table that summarizes the performance of a classification model. It compares the predicted labels with the actual labels in the test set. The matrix has four sections:

True Positive (TP): Instances that are actually positive and predicted as positive.
True Negative (TN): Instances that are actually negative and predicted as negative.
False Positive (FP): Instances that are actually negative but predicted as positive (Type I error).
False Negative (FN): Instances that are actually positive but predicted as negative (Type II error).
A good model will have high values on the diagonal (TP and TN) and low off-diagonal values (FP and FN).

# Classification Report:
The classification report provides a comprehensive evaluation of the model's performance. It includes the following metrics for each class (in this case, 'Malignant' and 'Benign'):

Precision: The ratio of true positives to the sum of true positives and false positives. It measures the accuracy of positive predictions.
Recall (Sensitivity or True Positive Rate): The ratio of true positives to the sum of true positives and false negatives. It measures the proportion of actual positives that are correctly identified.
F1-Score: The harmonic mean of precision and recall. It provides a single metric that balances both precision and recall.
Support: The number of occurrences of each class in the true dataset.
The classification report helps in understanding the model's performance on a per-class basis, providing insights into its strengths and weaknesses.