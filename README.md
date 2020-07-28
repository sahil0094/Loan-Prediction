![alt text](https://github.com/sahil0094/Loan-Prediction/blob/master/laon.png?raw=true)
# Loan-Prediction (Implementing ML In Tableau)
Housing Loan Company wants to automate the loan eligibility process (real time) based on customer detail provided while 
filling online application form. These details are Gender, Marital Status, Education, Number of Dependents, Income, Loan 
Amount, Credit History and others. To automate this process, they have given a problem to identify the customers segments,
those are eligible for loan amount so that they can specifically target these customers. .

## Approach-
It was a binary classification problem where we had to predict whether loan should be provided to a customer or 
not. We started with Logistic regression as it being a linear model and has low variance error. Then to improve the accuracy we 
went for tree based models and good variance and bias score for xgboost.

## Implementing ML in Tableau- 
I have made an interactive dashboard in Tableau where one has to enter the feature values which  are used for modeling and model result will be shown.
Using Tabpy , we have made a rest api which will be called once test parameters are entered for the model and corresponding results will be shown.

