# 🚀:Credit-Scoring-Analysis-Using-Regression-Models-and-Neural-Networks

## 📝 Description:
* Analyzing credit scoring data using various regression models (Ridge, Lasso, logistic regression) and a Neural Network model.
  
*  It highlights the techniques employed (regression and Neural Networks) and the domain of application (credit scoring).

## ⌛ Dataset:
* The dataset consists of financial metrics related to various companies, potentially sourced from their financial statements or annual reports.
  
*  Each row represents a different company, and each column represents a specific financial attribute or performance metric.
### 🎯: Response Variable (y):
* The response variable (dependent variable) is y, which represents the target variable 'InvGrd' containing the credit score rating.\
### 🎯: Target Varibale (x):
* All the predictor variables (independent variables) are contained in the DataFrame x. 
* These variables are used to predict the credit score rating. 
* They are obtained by dropping the columns 'Rating' and 'InvGrd' from the original dataset.
  
## 🖥️ Data Preprocessing:
* Dependent (x) and independent (y) variables are defined.
* Data is split into training and testing sets.
* Standardization is applied to the input features using StandardScaler.

## 🖥️ Model training and evaluation:
### Linear Regression Models:

* Both Ridge and Lasso regression models are implemented.
* The mean squared error is calculated for both models on the test set.
* The performance of Ridge and Lasso regression models is assessed based on their mean squared errors.
  
### Logistic Regression Models:

* Lasso and Ridge logistic regression models are implemented.
* The accuracy score is computed for both models on the test set.
* The performance of Lasso and Ridge logistic regression models is assessed based on their accuracy scores.
### Neural Network Model:

* A feedforward Neural Network model is defined with two hidden layers and an output layer.
* The model is trained using binary cross-entropy loss and the Adam optimizer.
* The accuracy of the model is evaluated on the test set.
* The accuracy achieved by the Neural Network model is reported.


