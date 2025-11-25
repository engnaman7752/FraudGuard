Credit-Card-Fraud-Detection-Using-Machine-Learning
ABSTRACT
Credit card fraud is a significant problem, with billions of dollars lost each year. Machine learning can be used to detect credit card fraud by identifying patterns that are indicative of fraudulent transactions. Credit card fraud refers to the physical loss of a credit card or the loss of sensitive credit card information. Many machine learning algorithms can be used for detection. This project proposes to develop and compare machine-learning models to detect credit card fraud. The models will be trained and evaluated on a historical dataset of credit card transactions, with a focus on metrics like Recall and F1-score which are crucial for imbalanced data.

Overview
With the increase of people using credit cards in their daily lives, credit card companies should take special care of the security and safety of the customers. According to (Credit card statistics 2021), the number of people using credit cards worldwide was 2.8 billion in 2019; also, 70% of those users own a single card. Reports of Credit card fraud in the U.S. rose by 44.7% in 2020. There are two kinds of credit card fraud. The first is having a credit card account opened under your name by an identity thief. Reports of this fraudulent behavior increased by 48% up to 2020. The second type is when an identity thief uses an existing account you created, usually by stealing the information on the credit card. Reports on this type of Fraud increased by 9% up to 2020 (Daly, 2021). Those statistics caught Naman Jain's attention as the numbers have increased drastically and rapidly throughout the years, which motivated him to resolve the issue analytically by using different machine learning methods to detect fraudulent credit card transactions within numerous transactions.

Project Goals
The main aim of this project is the detection of fraudulent credit card transactions, as it is essential to figure out the fraudulent transactions so that customers do not get charged for the purchase of products that they did not buy. Fraudulent Credit card transactions will be detected with multiple ML techniques, specifically focusing on handling the highly imbalanced nature of the dataset. Then, a comparison will be made between the outcomes and results of each method to find the best and most suited model for detecting fraudulent credit card transactions; graphs and numbers will also be provided. In addition, it explores previous literature and different techniques used to distinguish Fraud within a dataset.

Author Details
Name: Naman Jain

Email: nj260106@email.com

GitHub: engnaman7752

Data Source
The dataset was retrieved from an open-source website, Kaggle.com. It contains data on transactions made in 2013 by European credit card users in two days only. The dataset consists of 31 attributes and 284,808 rows. Twenty-eight attributes are numeric variables that, due to the confidentiality and privacy of the customers, have been transformed using PCA transformation; the three remaining attributes are "Time," which contains the elapsed seconds between the first and other transactions of each Attribute, "Amount" is the amount of each transaction, and the final attribute "Class" which contains binary variables where "1" is a case of fraudulent transaction, and "0" is not a case of fraudulent transaction.

Algorithm
K-Nearest Neighbor (KNN)

Logistic Regression (L.R.)

Random Forest (RF): Utilizing SMOTE (Synthetic Minority Over-sampling Technique) to balance the training data.

Gradient Boosting (GBM): Utilizing Class Weights to adjust the model's focus on the minority class.

Future Work
There are many ways to improve the model, such as using it on different datasets with various sizes and data types or by changing the data splitting ratio and viewing it from a different algorithm perspective. An example can be merging telecom data to calculate the location of people to have better knowledge of the location of the card owner while his/her credit card is being used; this will ease the detection because if the card owner is in Dubai and a transaction of his card was made in Abu Dhabi, it will easily be detected as Fraud. Future work will also include tuning hyperparameters and exploring advanced techniques like Isolation Forest or One-Class SVM for outlier detection.

Conclusion
In conclusion, the main objective of this project was to find the most suited model for credit card fraud detection in terms of the machine learning techniques chosen for the project. This involved exploring techniques beyond simple accuracy, specifically focusing on Recall and F1-Score for the minority (fraudulent) class. The models developed, particularly those incorporating methods for imbalanced data like SMOTE-enhanced Random Forest and Class Weight-adjusted Gradient Boosting, achieved high performance in identifying fraudulent transactions, which is essential for increased customer satisfaction and security.
