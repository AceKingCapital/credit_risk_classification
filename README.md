# credit_risk_classification
## Background
#### Credit risk poses a classification problem that’s inherently imbalanced. The reason is that healthy loans easily outnumber risky loans. For this Challenge, you’ll use various techniques to train and evaluate models with imbalanced classes.

## Procedure:
* Resampling of the dataset for the model's accurate prediction.
* Defining the logical regression model using the imbalanced-learn library to compare both the vesions of the same dataset: Original Data and the Resampled Training Data. 
* Resampling the original data using the RandomOverSampler module from the imbalanced-learn library.
* Analyzing the count of the target classes, training a logistic regression classifier, calculating the balanced accuracy score, generating a confusion matrix, and writing a summary report.

# Results Obtained:
## Machine Learning Model 1: Logistic Regression Model with the Original Data
* Accuracy: 95.20%
* Precision: 85%
* Recall: 91%

## Machine Learning Model 2: Logistic Regression Model with Resampled Training Data
* Accuracy: 99%
* Precision: 84%
* Recall: 99%

## Summary of Analysis:
#### The accuracy score of the resampled data (99%) is higher than the accuracy score of the original data (95%). Both the models have similar precission scores but the Logistic Regression Model with Resampled Training Data i.e., Model 2 has a higher recall rate (99%) as compared to Model 1 (91%). 
#### In conclusion, it will not be wrong to say that Model 2 i.e., the Logistic Regression Model with Resampled Training Data is a way better model than Model 1 i.e., the Logistic Regression Model with the Original Data.
