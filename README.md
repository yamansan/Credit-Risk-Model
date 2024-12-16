# Credit-Risk-Model
This project focuses on predicting loan defaults using a massive dataset of client information. Accurate predictions can help financial institutions minimize losses by identifying high-risk clients. The enormous dataset contains various features about the client's financial history and loan details. 

## Data Preprocessing/Cleaning
The dataset was preprocessed to handle missing values and encoded categorical features. Feature selection was performed to identify the most relevant attributes contributing to the prediction.


The goal is to use the features in order to predict the target value 1 (will default the loan) or 0 (will not default the loan). The accurcacy is measured using ROC AUC score which tells you how good the classifier is able to separate the 0s and 1s. We used LightGBM to make predictions and got a ROC-AUC score of 0.74. 
The data is given in the folder csv_files with train and test folders separately.
