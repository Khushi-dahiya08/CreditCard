# Credit Card Fraud Detection

This project uses machine learning techniques to detect fraud in credit card transactions. It applies various sampling methods to address class imbalance and evaluates the performance of different classifiers.

---

## Table of Contents

- [Installation](#installation)
- [Dependencies](#dependencies)
- [Data](#data)
- [Sampling Techniques](#sampling-techniques)
- [Machine Learning Models](#machine-learning-models)
- [Run the Code](#run-the-code)
- [License](#license)

---

## Installation

To get started, clone the repository and install the required dependencies.

1. Clone the repository:


2. Install the dependencies:


---

## Dependencies

To run this project, you need to install the following Python libraries:

1. **pandas**: A library for data manipulation and analysis.
2. **numpy**: A package for numerical computing in Python.
3. **scikit-learn**: A machine learning library that provides simple and efficient tools for data mining and data analysis.
4. **imbalanced-learn**: A package to handle imbalanced datasets, offering methods like SMOTE (Synthetic Minority Over-sampling Technique).

You can install them using the following command:


---

## Data

The dataset (`Creditcard_data.csv`) contains transaction data. The `Class` column represents whether a transaction is fraudulent (1) or not (0).

---

## Sampling Techniques

Various sampling methods are applied to handle the class imbalance in the dataset:

1. **Random Sampling**: This technique randomly selects a subset of the dataset, regardless of class distribution.
2. **Systematic Sampling**: Data is sampled at fixed intervals (e.g., every nth sample) to create a representative subset of the original data.
3. **Stratified Sampling**: This method ensures that the class distribution in the sample is similar to the distribution in the original dataset, maintaining the proportion of each class.
4. **SMOTE Sampling**: The Synthetic Minority Over-sampling Technique (SMOTE) generates synthetic samples for the minority class to help balance the dataset.
5. **SMOTE-ENN Sampling**: A combination of SMOTE and Edited Nearest Neighbors (ENN), this technique balances the dataset while cleaning noisy data by removing misclassified samples.

---

## Machine Learning Models

The following machine learning models are used for fraud detection:

1. **Logistic Regression**: A basic statistical model used for binary classification tasks.
2. **Random Forest**: An ensemble method that builds multiple decision trees and merges them to improve accuracy.
3. **Support Vector Machine (SVM)**: A classifier that identifies the optimal hyperplane to separate classes.
4. **K-Nearest Neighbors (KNN)**: A non-parametric algorithm that classifies data based on proximity to other labeled data points.
5. **Decision Tree**: A tree-like structure that makes decisions by splitting data based on feature values.

---

## Run the Code

To run the code, simply execute the following Python script:


This will apply the sampling techniques and train the models, showing accuracy scores for each combination of sampling method and classifier.

---

## License

This project is licensed under the **MIT License**.


