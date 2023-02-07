In this case, the database is a client retention status of a bank. 

Objective- Whether a client will continue with the bank or not.

In this case I have taken below steps (as per list). 

I explored various logistic regression techniques (Gaussian Naive Bayes, Logistic Regression, Decision Tree Classifier, KNN Classifier, Random Forest Classifier, XGB Classifier)  before venturing out to artificial neural network (ANN). Results from various logistic regression methods are presented along with confusion matrix. 
I compare the result with ANN method to find which path works best for the model. 

Work is broken down as per below list-

1.	Understand the shape of the data (drop irrelevant columns, check for null cells, explore unique values)

2.	Data Cleaning (no null values, hence no values were dropped)

3.	Data Exploration (histogram plot depending on client retention and various other parameters-tenure, gender etc)

4.	Feature Engineering (exploring which salary band / credit score band are leaving)

5.	Data Processing for Model (scaling the data)

6.	Basic Model Building (Gaussian Naive Bayes, Logistic Regression, Decision Tree Classifier, KNN Classifier, Random Forest Classifier, XGB Classifier)

7.	Confusion Matrix

Data source-Kaggle dataset (https://www.kaggle.com/datasets/barelydedicated/bank-customer-churn-modeling).
