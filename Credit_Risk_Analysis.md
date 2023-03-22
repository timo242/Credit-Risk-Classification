#  Credit Risk Analysis Report

##  Purpose of Analysis

The purpose of the Analysis is identify the creditworthiness of borrowers using an imbalance data set.  Provided two methods to predict the outcomes.  First, use the Logistic Regression model with the original data set.  Second, use the Logistic Regression model on oversampled data and compare the models accuracy on identifying credit worthy borrowers

## Analysis Results

### Logistic Regression Model
*              precision    recall  f1-score   support

       Healthy     1.00      0.99      1.00     18765
       High-Risk   0.85      0.91      0.88       619


### Logistic Regression Model using Oversampling
*              precision    recall  f1-score   support

       Healthy       1.00      0.99      1.00     18765
       High-Risk     0.84      0.99      0.91       619


##  Recommendations


The results of the two methods were near identical, however, the oversampled data did slightly better on the high-risk loans, than the original prediction. The F1 harmonic mean score for the oversampled prediction scored a 91, compared to the original prediction of 88. for the High-risk loans.  My recommendations would be to use the Logistic Regression with oversampling, until such a time where a lager dataset can be used to re-evaluate the methods
