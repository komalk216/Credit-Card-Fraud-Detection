# Credit-Card-Fraud-Detection
This repository includes the implementation of our BE project title "Credit Card Fraud Detection"
This is "Synapse" Company Sponsered Project
Under the guidance of Company we were supposed to refer the credit card fraud detection dataset from [Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) 

and Supposed to use LR and SVM for Model Training
After performing exploratory data analysis(refer EDA_CCFD.ipynb in this repo) we understand that dataset is highly imbalance
So we decide to create 4 different model by using different method for data imbalance handling and Model training and also we decided to perform feature selection using chi2
These Four models are  
      1)Oversampling and LR (SMOTE_LR_GUI.ipynb)
      2)Oversampling and SVM
      3)Undersampling and LR
      4)Undersampling and SVM (Random_SVM_GUI.ipynb)
Depending on our implementation and result and analysis we conclude that LR performs better with Oversampling while SVM performs better with undersampling.
We have created GUI for these both model
The major steps involved in this implementation are
      1)Loading dataset
      2)Data Preprocessing
      3)Data Imbalance handling
      4)Feature Extraction
      5)Model training and testing
      6)Result and Analysis
We have created GUI using tkinter in which we have fetch the record from testing dataset which we defined during splitting of our dataset into training and testing
this is done by using index of the transaction and on clicking button "Detect transaction type" window will display whether the transaction is fraud or not.

.pkl file present are created when we load our trained model using joblib library

Below are Screenshot of GUI of the System.

![Smote_LR](https://github.com/komalk216/Credit-Card-Fraud-Detection/assets/68997780/293317f6-f60a-496e-98f3-3e52f4741cfa)

![Random_SVM](https://github.com/komalk216/Credit-Card-Fraud-Detection/assets/68997780/a5de0d59-571f-4bb7-b3d4-101db910c6a2)
![Random_SVM (2)](https://github.com/komalk216/Credit-Card-Fraud-Detection/assets/68997780/2f2c7001-f376-4739-8f69-8fd063c0dba7)

