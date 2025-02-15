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
iv. Evaluation Metrics – The model will be evaluated using:
v. Precision, Recall, and F1-score to measure fraud detection accuracy.
vi. AUC-ROC (Area Under the Curve - Receiver Operating Characteristic) for overall classification performance.
vii. Precision-Recall AUC (since fraud detection is an imbalanced problem).

- 🔹 Final Outcome:
The goal is to develop a hybrid fraud detection model that combines supervised and unsupervised learning to accurately flag fraudulent rental transactions accurately, minimizing false positives while capturing fraudulent cases effectively.


## Dataset Link - <a href="https://www.kaggle.com/competitions/ieee-fraud-detection/data">IEEE-CIS Fraud Detection</a>
