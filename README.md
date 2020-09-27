# HR-Attrition-Rate

Introduction:

This fictional dataset is created by IBM data scientists and released on Kaggle. There are 1470 employee records in this dataset.

Objective - The purpose of this analysis is to uncover the factors that lead to employee attrition.

Framing our machine learning system -
1. Supervised learning - Since, we have labelled training data.
2. Classification - As we are identifying the features that affect employee attrition rate.

Selection of Performance Measure - Accuracy, Precision, Recall rate and ROC Curve

Assumptions - 
The top two important features that affect employee's attrition are -
  Employees working overtime and Employees taking business travel frequently.

This can also happen for many reasons:
  Employees looking for better opportunities.
  A negative working environment.
  Bad management
  Sickness of an employee (or even death)
  Excessive working hours
  
Based on above conditions, we will assume higher values of these conditions will result in more employee's would leave the company.
  
Steps followed -
1.We began by addressing the missing values.

2.We then explored by discovering the attrition rate by different features such as - Gender , business travels ,overtime , departments and job roles through variety of EDA plots.

3.We did preparation of data - by Feature encoding and scalling. 

4.Before deciding on regression models, we checked correlation between the features, and removed the non collinear features.

5.Also , Oversampling techniques (SMOTE) have been used to balance dataset.

6. In the final steps we applied various Machine Learning models: Logistic Regression, SVM, Random Forest, and XGBoost.
and found XGBoost is the best performing model with an accuracy score of about 89%.
