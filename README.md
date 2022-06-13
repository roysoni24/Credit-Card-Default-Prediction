# Credit Card Default Prediction
![CC IMAGE](https://user-images.githubusercontent.com/100474431/173319902-75a028c2-0e04-4603-ab5c-0d47ddc2922a.jpeg)
## **Predicting whether a customer will default on his/her credit card**

This project is aimed at predicting the case of customers default payments in Taiwan. From the perspective of risk management, the result of predictive accuracy of the estimated probability of default will be more valuable than the binary result of classification - credible or not credible clients. We can use the K-S chart to evaluate which customers will default on their credit card payments.

## **Data Description**

This research employed a binary variable, default payment (Yes = 1, No = 0), as the response variable. This study reviewed the literature and used the following 23 variables as explanatory variables:

  X1: Amount of the given credit (NT dollar): it includes both the individual consumer credit and his/her family (supplementary) credit.
  
  X2: Gender (1 = male; 2 = female).
  
  X3: Education (1 = graduate school; 2 = university; 3 = high school; 4 = others).
  
  X4: Marital status (1 = married; 2 = single; 3 = others).
  
  X5: Age (year).
  
  X6 - X11: History of past payment. We tracked the past monthly payment records (from April to September, 2005) as follows: X6 = the repayment status in September,     2005; 
  X7 = the repayment status in August, 2005; . . .;
  
  X11 = the repayment status in April, 2005. The measurement scale for the repayment status is: -1 = pay duly; 1 = payment delay for one month; 2 = payment delay for two   months; . . .; 8 = payment delay for eight months; 9 = payment delay for nine months and above.
  
  X12-X17: Amount of bill statement (NT dollar). X12 = amount of bill statement in September, 2005; X13 = amount of bill statement in August, 2005; . . .;X17 = amount of bill statement in April, 2005.
  
  X18-X23: Amount of previous payment (NT dollar). X18 = amount paid in September, 2005; X19 = amount paid in August, 2005; . . .;X23 = amount paid in April, 2005.
  
  ## **Appraoch Pipeline**
  
  Data Preprocessing
  
  Data Exploration
  
  Model Prediction
  
  ## **Conclusion**
  
 1. From all baseline model, Random Forest classifier shows highest test accuracy
and F1 score and AUC.

2. Baseline model of Random Forest and decision tree shows huge difference in
train and test accuracy which shows overfitting.

3. After cross validation and hyperparameter tunning, XG Boost shows highest test
accuracy score of 87% and AUC is 0.873.

4. Cross validation and hyperparameter tunning certainly reduces chances of
overfitting and also increases performance of model.
  
  
