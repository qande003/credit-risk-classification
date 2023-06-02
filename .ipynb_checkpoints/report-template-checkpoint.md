# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.

    The purpose of the analysis is two test two linear regression models, one with the original data and the second to resample the imbalanced data. The analysis also provides us with an accuracy scores and a balanced accuracy score. It also shows that the high accuracy scores produced allow us to make accurate predications. 

* Explain what financial information the data was on, and what you needed to predict.

The dataset used historical lending activity from a peer-to-peer lending services company which was used to build a model that can identify the creditworthiness of borrowers.

* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).

The dataset included 75,036 occurrences of healthy loans and 2,500 of high-risk loans. The oversampling model harmonized both types of loans to 75,036 occurrences.

* Describe the stages of the machine learning process you went through as part of this analysis.

The first stage of the machine learning process was splitting the data into training and testing sets, followed by creating a logistic regression model with the original data. I then created a logistic regression model with resampled training data and now creating the analysis.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.

Accuracy (Overall): 95.2%
Precision (Healthy / High-Risk): 1.00 / 0.85
Recall (Healthy / High-Risk): .99 / 0.91

* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.

Accuracy (Overall): 99.5%
Precision (Healthy / High-Risk): 1.00 / 0.99
Recall (Healthy / High-Risk): .99 / 1.00

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

Machine Learning Model 2 had an overall higher accuracy and precision in predicting all high-risk loans and maintained great performance in terms of precision. I would recommend this modeul when trying to determine the creditworthiness of potential borrowers going forward.



