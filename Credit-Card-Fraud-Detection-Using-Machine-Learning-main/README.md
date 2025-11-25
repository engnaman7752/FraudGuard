💳 Credit Card Fraud Detection Using Machine Learning
📌 Abstract

Credit card fraud is a rising global concern, resulting in billions of dollars in annual financial losses. Machine learning provides a powerful means to detect fraud by identifying unusual patterns in transaction behavior. This project develops and compares machine learning models trained on historical credit card transaction data, with performance evaluated using metrics such as Recall and F1-Score, which are essential for imbalanced classification problems.

📘 Overview

The popularity of credit cards has surged, with 2.8 billion users worldwide as of 2019, and fraud cases have significantly increased. Reports show:

+48% increase in identity-based fraud (new accounts created by thieves)

+9% increase in unauthorized use of existing accounts

This project explores machine learning solutions to identify fraudulent transactions from legitimate ones using analytical and predictive modeling techniques.

🎯 Project Goals

Detect fraudulent transactions effectively.

Apply multiple ML models and evaluate their performance.

Handle class imbalance using methods such as:

SMOTE (Synthetic Minority Oversampling Technique)

Class Weight Adjustment

Compare and select the most effective model based on Recall and F1-Score.

👤 Author
Field	Details
Name	Naman Jain
Email	nj260106@email.com

GitHub	engnaman7752
📁 Dataset

Source: Kaggle

Rows: 284,808 transactions

Duration: 2 days

Features: 31

28 PCA-transformed numerical features

Time (elapsed seconds between transactions)

Amount (transaction value)

Class (Label: 1 = Fraud, 0 = Not Fraud)

⚙️ Machine Learning Models Used

K-Nearest Neighbors (KNN)

Logistic Regression

Random Forest (with SMOTE)

Gradient Boosting (with class weighting)

🛠 Technologies Used

Python

Pandas

NumPy

Scikit-learn

Matplotlib

Seaborn

SMOTE (Imblearn)

🚀 Future Improvements

Train and test on larger, real-world datasets.

Integrate external behavioral data (e.g., geolocation).

Experiment with advanced anomaly detection models:

Isolation Forest

Autoencoders

One-Class SVM

Apply hyperparameter tuning and real-time deployment.

🏁 Conclusion

This project identifies the best-performing machine learning model for detecting fraudulent credit card transactions by emphasizing Recall and F1-score rather than overall accuracy. Approaches that addressed class imbalance, such as SMOTE with Random Forest and class-balanced Gradient Boosting, showed the strongest ability to correctly identify fraudulent activity, improving user safety and reducing financial losses.
