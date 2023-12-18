Credit Card Fraud Detection:

The dataset contains transactions made by credit cards in September 2013 by European cardholders.This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. 
The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

1. We imported the Data, The Data was already Trasformed with PCA transformation, However the column Amount was not transfomed, we transformed it by standard scaler transformation, checked for null vlaues, Duplicates,Dropped the Time column since it did not have any 
   signification relationship with the output. 

2. Since it had highly imbalance data we undersampled it and checked the output. Then performed Logistic Regression and Random Forest to get the accuracy score as 0.945 and 0.95 accordingly.

3. Again we oversampled it by SMOTE method and then checked with the Logistic Regression and Random Forest to get the accuracy score as 0.94 and 0.999.

4. Hence the accuracy, Precesion , recall, f1score with Random forest Algo is Better after Smote Trasformation. we saved the model.

5. Predicted for a test case if the model is model predicts whether the transaction is Fraud or Normal.
