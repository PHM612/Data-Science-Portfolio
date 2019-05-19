# Credit Card Fraud Detection

![](https://images.pexels.com/photos/164571/pexels-photo-164571.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940)

Dataset from : https://www.kaggle.com/mlg-ulb/creditcardfraud/downloads/creditcardfraud.zip/3

## Context

It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase.

## Data

The datasets contains transactions made by credit cards in September 2013 by european cardholders. This dataset presents transactions that occurred over two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced.

Most of the provided features result from a PCA transformation, due to confidentiality concerns from the data providers.

The features are :
- Time: time in second relative to the first transaction
- V1 to V28: PCA outputs
- Amount: the amount of the transaction
- Class: whether the transaction is fraudulent (1) or not (0)

## Metric

Given the class imbalance ratio, the metric used to compute the performance of the model will be the Area Under the Precision-Recall Curve (AUPRC). 