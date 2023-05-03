# Credit_card_default_prediction
The aim of a credit card default prediction project is to develop a machine learning model that can accurately predict which credit card users are likely to default on their payments in the future. The model should use historical data of credit card users such as their payment history, credit limit, age, education, and other demographic information to identify patterns and trends that can help predict default behavior. The project focuses on utilizing historical data of Customer's default payment in Taiwan.


The purpose of this project is to conduct quantitative analysis on credit card default risk by using 3 machine learning models with accessible customer data, instead of credit score or credit history, with the goal of assisting and speeding up the human decision making process.

Our project is divided into several parts :

* The first stage is to underatand the dataset that involves data inspection which included first view of data,looking for missing values and duplicate values.
* The next stage involved exploratory data analysis, where trends and patterns in the data were identified. Distribution of data was also studied.
* Hypothesis Testing was performed.
* After this Feature selection and Preprocessing of data was done by converting categorical variables into numerical ones, splitting data, data scaling and also handle the imbalance data.
* Furthur, various machine learning algorithms were tested on the split data that is trainig and test dataset, including Logistic regression, Random Forest Classifier and XGBOOST classifier.
* In the last part we evaluate the evaluation metrics of each algorithm and implement the machine learning algorithm  with better scores. 

Some of following insights are:
* There were **30000 records and 25 attributes** in the dataset. 
* In feature engineering we transformed raw data into a more useful and informative form, by encoding, feature manipulation, and feature selection. We handled target class imbalance using **SMOTE**.
* When implementing a machine learning model, We focused more on the Recall score and F1 score because we are dealing with credit card data and our data is unbalanced.
* After comparing all the metrices like Recall and f1 score, I found out XGBOOST classifier is most suitabe machine earning alogrithm for this business problem.

Overall Credit card default prediction demonstrate the best use of machine learning algorithm in predicting the number of defaulters in banking sector.
