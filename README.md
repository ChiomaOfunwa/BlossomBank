# BlossomBank
10alytics Cohort10 Capstone Project 
Machine Learning Model built to detect and predict online payment fraud
Data Acqusition was done.
The libraries were imported(numpy, pandas,seaborn and matplotlib) and used to get the information of the dataset, describe, visualize and analyze the dataset.
The dataset contains 10 columns and 1048575rows with no duplicated value and missing value.
Data cleaning was done( which involves Exploratory Analysis of the data), Using the Univariate and Multivairiate method of data exploration.
Using the distplot on the numerical variable, I observe that the amount is positively skewed.
The countplot was used to visulaize the target label which is "isFraud" and found 1142 fraud transactions(0.11%).
Distribution of payment type was checked using the countplot and we found that the cashout payment type is the most used payment platform, followed by the payment platform.
Using the multivariate method of data exploration, I observed that the cash-out and transfer payment type are the platforms where the frauds were detected.
Using Corr() to check the variable correlation, The relationship between the newbalanceOrig and oldbalanceOrg has the best correlation.
Created a new column 'IsFraud' whcih converted the 'isFraud' numerical values to a categorical value
The 'isFraud' column was dropped.
Encoded the target label "IsFraud" and the "type" label as they are categorical variable.
Columns that are not needed were dropped.
Scaled the dataset using Standard Scaler
Splitted the target label using 70-30 moethod of training data and testing data.
Supervised Algorithms were used to train 70% of the data and target.
Used Naive Bayes, Logistics Regression and Decision Tree Algorithms was used.
Then the performace of the 3 Algorithms was evaluated and the Decision Tree was found to be one with the best accuracy with 91% accuracy.
