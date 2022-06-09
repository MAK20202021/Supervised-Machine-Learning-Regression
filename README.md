# Supervised-Machine-Learning-Regression

This exercise is the combination of the following three topics:
-  Linear Regression
-  Cross Validation and Grid Search
-  Regularization (Lasso and Ridge Regression) and Gradient Descent 

Linear Regression is mainly the linear combinations of features, however, we can add some nonlinearities of the features to get more accurate results. We used polynomialfeatures from preprossessing library. We have analized the bais and variance where baia is a tendency to miss and variance is tendency to be inconsistent. The higher degree of a polynomial regression, the more complex the model which has lower bias and higher variance. The main goal is to find the right degree such that the model has sufficient complexity to describe the data without overfitting. Then we have focused on the train and test splitting of the data set to evaluate the model accurately with the test set. Cross validation and Grid search can provide us more accurate model by tunning hyperparameters. 

Regularization performs feature selection by reducing the contribution of features which prevents overfitting. Identifying most critical features can improve the model interpretability. Scaling is very important before regularization. In case of Ridge regression, the complexity penalty (lambda) is proportonal to the square of the coefficients and in case of Lasso regression, the complexity penalty (lambda) is proportonal to the absolute value of the coefficients. Compared with Lasso regression (assuming similar implementation) Ridge regression is less likely to set feature coefficients to zero. 
 

At last, we completed a combined project which reflects all the above topics together. 
We chose Ames Housing Data which involves the lot area, all other amenities of the housing and corresponding sale price.
At the beginning, we do EDA to get initial idea about the data, then did some feature engineering to get the useful features before 
building the machine learning model. At last we evaluated our results by performing hypothesis testing.

## Acknowledgement
This exercise is for [IBM Machine Learning Professional Certificate Program](https://www.coursera.org/professional-certificates/ibm-machine-learning?).
Thanks to Coursera and IBM for arranging this exercise to strengthen our knowledge. 
## Installation
This exercise needs Anaconda package(Anaconda3), Jupyter Notebook (6.1.4).

## File Description
The source codes and Data files are as follows:
- Ames_Housing_Sales.csv
- boston_housing_clean.pickle
- Linear Regression Exercise.ipynb
- Linear Regression_Train_Test_Split.ipynb
- Cross_Validation_gridSearchCV.ipynb
- Regularization_and_Gradient_Descent.ipynb
- Smart_home_dataset.7z
- Project_Supervised_ML_Regression.ipynb
- Project_Supervised_ML_Regression.html
- Project_Supervised_ML_Report.pdf


## Discussion
After completing this exercise, I understand how we can build supervised machine learning linear regression model and in addtion we can find the utilization of Lasso and Ridge model to prevent from the overfitting problem.
