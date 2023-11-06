# Multiclassification_Credit_Score_Project (Banking)

Over the years, the company has collected basic bank details and gathered a lot of credit-related and loan information of bank customers. The dataset includes 27 features describing customers information about age, occupation, number of bank accounts, monthly inhand salary, type of loan, EMI per month, credit utilization ratio, credit history age, payment behaviour, monthly balance, etc.

The aim is to build an intelligent system to segregate the people into credit score brackets to reduce manual efforts.

The objective of this project is to explore the data to identify the pattern that causes the person to have a good or bad or standard type credit score and build a machine learning model that should be able to predict or classify the credit score type of bank customers. 

Various data cleaning operations are performed. Null entries were replaced by median values obtained after grouping the records of relevant customers.

Feature engineering, oulier treatment is performed before train test split. Performance of various ML algorithms such as decision tree, random forest, Adaboost, Gradient-boost, XGBoost were used.

The parameters were hypertuned in the end to improve model performance. By using the model, bank customers in test dataset were classified with 78% accuracy.
