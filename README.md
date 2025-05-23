# Naive Bayes Classifier from Scratch

This project implements a Naive Bayes classifier from scratch to predict whether a student will fail a course based on a given set of features. The implementation avoids using pre-built machine learning libraries for the core algorithm, providing a deeper understanding of how Naive Bayes works under the hood.

## Overview

The goal of this lab is to classify students into two categories: **Fail** or **Pass**, based on their features such as attendance, assignment scores, and exam performance. The Naive Bayes algorithm is chosen for its simplicity and effectiveness in handling categorical and numerical data.

The project also includes a comparison of the custom implementation with Scikit-learn's Naive Bayes classifier to validate the correctness of the implementation.

## Key Features

- **Custom Naive Bayes Implementation**: Implements the Naive Bayes algorithm from scratch, including:
  - Calculation of prior probabilities.
  - Likelihood estimation for categorical and numerical features.
  - Prediction based on the maximum posterior probability.

- **Metrics Evaluation**: Computes key performance metrics to evaluate the model:
  - Accuracy
  - F1 Score
  - Precision
  - Recall

- **Comparison with Scikit-learn**: Validates the custom implementation by comparing predictions with Scikit-learn's Naive Bayes classifier.

## Key Functions

### `train_naive_bayes(X_train, y_train)`
Trains the Naive Bayes model by calculating prior probabilities and feature likelihoods.

### `predict_naive_bayes(X_test)`
Predicts the class labels for the test dataset using the trained Naive Bayes model.

### `compute_metrics(y_true, y_pred)`
Calculates performance metrics (Accuracy, F1 Score, Precision, Recall) to evaluate the model's performance.

### `compare_with_sklearn(X_train, y_train, X_test)`
Compares the predictions of the custom Naive Bayes implementation with Scikit-learn's implementation to ensure correctness.


