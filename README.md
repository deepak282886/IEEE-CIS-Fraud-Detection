IEEE-CIS Fraud Detection
Link to the problem:- https://www.kaggle.com/c/ieee-fraud-detection/overview

The following case study contains card transactions data from vesta - e-commerce payment solution provider and we have to use that to identify fraudulent transactions.

Dataset

a. Train_transaction.csv and Test_transaction.csv - These files contain the details of product being purchased, card used, addresses, emails, amount of transaction etc.

b. Train_identity.csv and Test_identity.csv - These csv files contain details like device type, device info etc. - named. The identify file does not contain values for each transaction i.e. it has lots of missing data.

Problem statement and Metric:-

We are required to obtain the probability of each transaction being fraud from the dataset and the results will be evaluated on the area under the ROC curve between the predicted probability and the observed target.
