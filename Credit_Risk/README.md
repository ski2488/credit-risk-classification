# credit-risk-classification
# Module 20 Report

## Overview of the Analysis

In this module, we looked at lending data and sought to apply logistic regression to predict 'healthy' vs 'high risk' loans. 
The data set included variables such as: loan size, interest rate, debt:income and total debt. The data had a total of just over 77.5k loans, of which 2,500 were 'high risk'. In order to perform the logistic regression the data was split into training and test sets using both stratified sampling (Model 1) as well as random oversampling (Model 2). 

## Results

The results were as follows for each model:

* Model 1: Stratified Sampling
  * Accuracy: 99.24%
  * Balanced Accuracy: 94.42% 
  * Precision: 99.64%
  * Recall: 87.46%

* Model 2: Random Oversampling
  * Accuracy: 99.52%
  * Balanced Accuracy: 99.60%
  * Precision: 99.99% 
  * Recall: 87.25%


## Summary

Overall, Model 2 performs better in terms of both accuracy and precision. Model 2 improves on the precision versus Model 1, meaning the lender can be more certain of the healthy loans in their portfolio and the characteristics of healthy loans for prospective lenders in the future - this will increase profits! Unfortunately, Model 2 has a slightly lower recall (meaning it is more likely to misclassify 'high risk' loans) but the difference is relatively small versus Model 1. 


