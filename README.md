# SageMaker Payment Classification¶

# Background 
Train and deploy a machine learning model to classify payment transactions.  Overview of consumer spending habits through XGBoost algorithm and trained and deployed in Amazon Sagemaker. For this notebook a generated dataset is used where a payment consists of mostly an amount, sender, receiver and timestamp.

# Dataset 
For this notebook we use a synthetic dataset. This dataset has the following features

transaction_category: The category of the transaction

receiver_id: an identifier for the receiving party. The identifier consist of 16 numbers.

sender_id: an identifier for the sending party. The identifier consist of 16 numbers.

amount: the amount which is transferred.

timestamp: the timestamp of the transaction in YYYY-MM-DD HH:MM:SS format
