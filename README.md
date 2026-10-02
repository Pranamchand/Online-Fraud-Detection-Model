# Online Payment Fraud Detection

A notebook project exploring transaction data and comparing machine learning models for fraud detection.

## Project overview

The notebook explores transaction patterns, prepares features, and trains models to classify transactions as fraudulent or legitimate.

## Method

- Encodes transaction type and scales numeric features.
- Compares Logistic Regression, Decision Tree, Random Forest, K-Nearest Neighbors, and Naive Bayes.
- Evaluates models using precision, recall, F1 score, and ROC-AUC.

## Result

The Decision Tree had the highest F1 score in this comparison: **0.9031**. Since fraud cases are rare, accuracy alone may not reflect model performance well.

## Dataset and tools

The notebook uses the Online Payment Fraud Detection dataset from Kaggle. Tools include Python, pandas, NumPy, Matplotlib, Seaborn, and scikit-learn.
