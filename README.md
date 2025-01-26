# Credit Card Fraud Detection

This project detects credit card fraud using machine learning models while addressing class imbalance. It tests multiple sampling techniques to balance the dataset and evaluates several classifiers.

## Installation

Clone the repo and install dependencies:

```bash
git clone https://github.com/your-username/credit-card-fraud-detection.git
cd credit-card-fraud-detection
pip install -r requirements.txt
Dependencies
pandas
numpy
scikit-learn
imbalanced-learn
Data
The dataset (Creditcard_data.csv) contains transaction data, with the Class column indicating fraud (1) or not (0).

Sampling Techniques
Random Sampling
Systematic Sampling
Stratified Sampling
SMOTE Sampling
SMOTE-ENN Sampling
Machine Learning Models
Logistic Regression
Random Forest
SVM
KNN
Decision Tree
python fraud_detection.py
