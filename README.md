# Credit Card Default Prediction
**AlmaBetter Verfied Project**
![CC IMAGE](https://user-images.githubusercontent.com/100474431/173319902-75a028c2-0e04-4603-ab5c-0d47ddc2922a.jpeg)

# 📋 Problem Statement
### **Predicting whether a customer will default on his/her credit card**

This project is aimed at predicting the case of customers default payments in Taiwan. From the perspective of risk management, the result of predictive accuracy of the estimated probability of default will be more valuable than the binary result of classification - credible or not credible clients. 
## **Data Description**

This research employed a binary variable, default payment (Yes = 1, No = 0), as the response variable. This study reviewed the literature and used the following 23 variables as explanatory variables:

  X1: Amount of the given credit (NT dollar): it includes both the individual consumer credit and his/her family (supplementary) credit.
  
  X2: Gender (1 = male; 2 = female).
  
  X3: Education (1 = graduate school; 2 = university; 3 = high school; 4 = others).
  
  X4: Marital status (1 = married; 2 = single; 3 = others).
  
  X5: Age (year).
  
  X6 - X11: History of past payment. We tracked the past monthly payment records (from April to September, 2005) as follows: X6 = the repayment status in September,     2005; 
  X7 = the repayment status in August, 2005; . . .; X11 = the repayment status in April, 2005. The measurement scale for the repayment status is: -1 = pay duly; 1 = payment delay for one month; 2 = payment delay for two   months; . . .; 8 = payment delay for eight months; 9 = payment delay for nine months and above.
  
  X12-X17: Amount of bill statement (NT dollar). X12 = amount of bill statement in September, 2005; X13 = amount of bill statement in August, 2005; . . .;X17 = amount of bill statement in April, 2005.
  
  X18-X23: Amount of previous payment (NT dollar). X18 = amount paid in September, 2005; X19 = amount paid in August, 2005; . . .;X23 = amount paid in April, 2005.
  
  ## **Appraoch Pipeline**
  
  Data Preprocessing
  
  Data Exploration
  
  Model Prediction
  
 ## 💾 Project Files Description
 
This Project includes 1 colab notebook and 1 Pdf of presentation.

### **Executable Files:**

[Credit-Card-Default-Prediction](https://github.com/roysoni24/Credit-Card-Default-Prediction/blob/main/Credit_Card_Default_Prediction_Capstone_Project.ipynb) - Includes Exploratory Data Analysis and all algorithms which are used in this project.

[credit card default prediction.pdf ](https://github.com/roysoni24/Credit-Card-Default-Prediction/blob/main/credit%20card%20default%20prediction.pdf)- Includes pdf of the presentation of the project.

### **Output:**

[Google Colab](https://github.com/roysoni24/Credit-Card-Default-Prediction/blob/main/Credit_Card_Default_Prediction_Capstone_Project.ipynb) - All the outputs are visible in the provided colab notebook.

## 📋 **Execution Instruction**

The order of execution of the colab notebook is as follows:

**1) Credit_Card_Default_Prediction_Capstone_Project.ipynb**

First, click on the open in colab button present on the top center of the notebook.

In this .ipynb file, we have -

• EDA on credit card default prediction.

• Handling class imbalance 

• Fitting different models and cross validate them.

**2) Kaggle Dataset**

Downlaod the dataset from kaggle through provided link.Then, connect to the runtime and execute the cell to mount the drive or upload the data file to the current runtime.

**3) Cell Path**

Finally, delete the path in the dataset loading cell and replace it with the path of your current data file. Run each cell to see the output below it.

## **Algorithms**

1. XG Boosting
2. Gradient Boosting
3. Support Vector Machine
4. Random Forest Classifier
5. Decision Tree Classifier
6. Logistic Regression
  
## **Conclusions**
  
 1. From all baseline model, Random Forest classifier shows highest test accuracy
and F1 score and AUC.

2. Baseline model of Random Forest and decision tree shows huge difference in
train and test accuracy which shows overfitting.

3. After cross validation and hyperparameter tunning, XG Boost shows highest test
accuracy score of 87% and AUC is 0.873.

4. Cross validation and hyperparameter tunning certainly reduces chances of
overfitting and also increases performance of model.

## 📜 **Credits**
Soni Rani | Vivek Kumar | Suraj Singh

## 📚 **References**
Using SMOTE - https://machinelearningmastery.com/smote-oversampling-for-imbalanced-classification/

XGBoost Documentation - https://xgboost.readthedocs.io/en/stable/

SVM - https://scikit-learn.org/stable/modules/generated/sklearn.svm.SVC.html
  
  
