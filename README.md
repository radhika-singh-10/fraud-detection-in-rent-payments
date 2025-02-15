# Fraud Detection in Rent Payments

The project aims to detect fraudulent transactions in rental payments using machine learning techniques. It involves analyzing historical tenant behavior and transaction data to identify patterns that distinguish fraudulent activities from legitimate ones.


# 🔹 Key Aspects of the Task:

- Fraud Detection – The primary goal is to build a model to accurately identify fraudulent rent payments.
Supervised and Unsupervised Learning – Using labeled data for supervised models (e.g., XGBoost, Logistic Regression) and anomaly detection for unsupervised models (e.g., Isolation Forest, One-Class SVM).

- Handling Imbalanced Data – Since fraud cases are rare, techniques like SMOTE (Synthetic Minority Over-sampling Technique) and class weighting will be used.

- Feature Engineering – Creating meaningful features such as:
  
   i. Time-based spending patterns.

   ii. Transaction frequency analysis.

   iii. Anomaly detection based on transaction locations and amounts.

iv. Evaluation Metrics – The model will be evaluated using:  Precision, Recall, and F1-score to measure fraud detection accuracy, AUC-ROC (Area Under the Curve - Receiver Operating Characteristic) for overall classification performance,  Precision-Recall AUC (since fraud detection is an imbalanced problem).

## 🔹 Final Outcome:
The goal is to develop a hybrid fraud detection model that combines supervised and unsupervised learning to accurately flag fraudulent rental transactions accurately, minimizing false positives while capturing fraudulent cases effectively.


## 🏗 Model Approaches

## 1️⃣ Unsupervised Learning (Anomaly Detection)

- Isolation Forest: Detects anomalies by randomly isolating data points.

- Anomaly Score Conversion: Converts anomaly detection results into binary labels (1 = Fraud, 0 = Normal).

## 2️⃣ Supervised Learning (Classification)

- XGBoost: A gradient-boosting model trained with both normal transaction features and anomaly scores.

## Handling Imbalanced Data:

- SMOTE (Synthetic Minority Over-sampling Technique) to generate synthetic fraud cases.

- Class Weighting in Loss Function to improve fraud detection.

## 📊 Evaluation Metrics

- Confusion Matrix: The confusion matrix provides an overview of model performance:

i. True Positive (TP): Correctly identified fraud cases.

ii. True Negative (TN): Correctly identified non-fraud cases.

iii. False Positive (FP): Non-fraud cases incorrectly classified as fraud.

iv. False Negative (FN): Fraud cases incorrectly classified as non-fraud.

## Dataset Link - <a href="https://www.kaggle.com/competitions/ieee-fraud-detection/data">IEEE-CIS Fraud Detection</a>
