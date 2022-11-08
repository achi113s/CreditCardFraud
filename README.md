# Credit Card Fraud

This is a machine learning exercise using the Credit Card Fraud Detection dataset on Kaggle (https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

The objective is to use the features to train a machine learning model to detect whether a transaction is fraudulent or not. The challenge with this dataset is that it is horribly imbalanced, with a non-fraudulent:fraudulent ratio of 99.828. The input features have already been transformed by Principal Component Analysis (PCA) and so we do not know what each feature represents. The only features not transformed are 'Time' and 'Amount'.