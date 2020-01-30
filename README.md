# Credit-Card-Fraud-Detection

### Problem Statement:

The Credit Card Fraud Detection Problem includes modeling past credit card transactions with the knowledge of the ones that turned out to be fraud. This model is then used to identify whether a new transaction is fraudulent or not. Our aim here is to detect 100% of the fraudulent transactions while minimizing the incorrect fraud classifications.

### Data Set Analysis:

This problem has been picked from Kaggle.



### Observations

1. The data set is highly skewed, consisting of 492 frauds in a total of 284,807 observations. This resulted in only 0.172% fraud cases.
2. This skewed set is justified by the low number of fraudulent transactions.
3. The dataset consists of numerical values from the 28 ‘Principal Component Analysis (PCA)’ transformed features, namely V1 to V28.
4. Furthermore, there is no metadata about the original features provided, so pre-analysis or feature study could not be done.
5. The ‘Time’ and ‘Amount’ features are not transformed data.
6. There is no missing value in the dataset.

###Autoencoders

   Autoencoding is a data compression algorithm where the compression and decompression functions are
          1. Data Specific
          2. Lossy
          3. Learned automatically from the examples.
     
      An autoencoder neural network is an unsupervised learning algorithm that applies backpropogation, setting the target values to be equal to the inputs.
