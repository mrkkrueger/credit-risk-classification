# credit-risk-classification
Code for this assignment can be found on the main page of this repository in the file called 'cred_risk_classification.ipynb'. Code for this project came from class notes, instructor demonstration, and the use of ChatGPT. The credit risk analysis report can be found in the text below.

#Credit Risk Analysis Report

## Overview of the Analysis

The purpose of this analysis was to train and evaluate a model to predict loan risk. The dataset included information about size of the loan, intereste rate, income, debt to income ratio, number of accounts, any derogatory marks, total debt, and the status of the loan. The data was split into training and testing sets and then a logistical regression model was created using the original data and resampled training data.


## Results
* Machine Learning Model 1:
  *The first model does a great job of predicting healthy loans. For healthy loans, the precision is 1.00 and the recall is 0.99. It isn't as accurate at predicting high risk lonas, but still does a good job with a precision of 0.85 and a recall of 0.91.

* Machine Learning Model 2:
  *The second model aslo does a great job of predicting heatlhy loans. For healthin loans, the precision is 1.00 and the recall is 0.99. It also does a good job at predicting high risk loans, with a precision of 0.84 and recall of .99

## Summary

Both models apepar to do a good job at predicting loan health. The precision and recall scores for healthy loans were the same for both models. But if you look at the raw numbers, the second model did slightly better, It was able to to reduce the number of incorrectly predicted loans by 52. However, as it had predicted over 18,000 healthly loans, this increase is accuracy is likely not statistically significant.
The second had slightly worse precision when it came to predicting high-risk loans (.85 for model 1 vs .84 for model 2). However, it had much better recall (.91 for model 1 vs .99 for model 2). Because of this, I would recommend using model 2. 

