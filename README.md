# Credit-card-Fraud-detection
This project aims to build a machine learning model that can effectively detect fraudulent transactions from a credit card dataset. Fraud detection is crucial for financial institutions, and this model helps identify fraudulent transactions to minimize loss and protect customers.

The dataset used contains anonymized features about credit card transactions, and the task is to classify transactions as either fraudulent (positive class) or legitimate (negative class). The dataset is highly imbalanced, with the majority of transactions being legitimate.
Dataset
The dataset  which is used for this project contains credit card transactions made by European cardholders in September 2013. It consists of 284,807 transactions over a period of two days, of which 492 are fraudulent, making the dataset highly imbalanced (fraud cases constitute only 0.172% of all transactions).

Key Features:

Time: Seconds elapsed between each transaction and the first transaction in the dataset.

Amount: Transaction amount, which can be used for cost-sensitive learning.

V1 to V28: Principal components derived via PCA (due to confidentiality issues, the original features are not available).

Class: Target variable (1 for fraud, 0 for non-fraud).

Class Distribution

Fraud cases: 492 (0.172%)

Non-fraud cases: 284,315 (99.828%)

Tools and Libraries

Python

Scikit-learn

Pandas

NumPy

Seaborn for visualizations

RandomForest Classifier

Result

After training and testing on the dataset, the final model achieved an accuracy score of 0.982, demonstrating its robustness and reliability in making predictions based on the given features.

