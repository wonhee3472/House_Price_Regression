# Predicting the final price of residential homes in Ames, Iowa

## 1. Problem Definition
> How well can I predict the future sale price of each residential homes in Ames, Iowa given its characteristics?

## 2. Data
The data has been downloaded from `House Prices - Advanced Regression Techniques` (https://www.kaggle.com/c/house-prices-advanced-regression-techniques/overview)

* train.csv - the training set
* test.csv - the test set
* data_description.txt - full description of each column, originally prepared by Dean De Cock but lightly edited to match the column names used here

## 3. Evaluation
The evaluation metric for this competition is the Root-Mean-Squared-Error (RMSE) between the logarithm of the predicted value and the logarithm of the observed sales price. (Taking logs means that errors in predicting expensive houses and cheap houses will affect the result equally.)

It is your job to predict the sales price for each house. For each Id in the test set, you must predict the value of the SalePrice variable. 
