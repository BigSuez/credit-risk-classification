# Credit Risk Classification

## Goals

* Analyize Credit Risk using Supervised Machine Learning

## Tools Used

* Jupyter Notebooks
* Pandas
* Sklearn
* Logistic Regression

## Report
### Machine Learning Model Stats
  * Balanced Accuracy Score of .95
  * Precision of 1.0 for Healthy Loans, .85 for High-Risk
  * Recall of .99 for Healthy Loans, .88 for High-Risk
### Summary

The model performed very well predicting Healthy Loans, but slightly less so for High-Risk Loans. As such, this model could be used to confidently classify Healthy Loans, which the majority are. While the model does a decent job at predicting High-Risk loans, an f1-score of .88 means that it will require manual oversight to confirm the results of the predictions. While High-Risk Loans are likely more important to identify, as they can lead to greater loss, the models utility for Healthy Loans can be used to significantly cut down on the overall labor required to classify loans.
