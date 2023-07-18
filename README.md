Credit Risk Analysis Report

Background: In this Challenge, you’ll use various techniques to train and evaluate a model based on loan risk. You’ll use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

An overview of the analysis:
  - The goal of this analysis is to "use various techniques to train and evaluate a model based on loan risk".
  - The purpose is to "build a model that can identify the creditworthiness of borrowers" using the "dataset of historical lending activity from a peer-to-peer lending services company". 

Stages / process:
1. Splitting the data into training & testing
2. Creating logistic regression model (original data)
3. Evaluating performance (accuracy, confusion matrix, & classification report)

The results: 

Machine Learning Model 1:(* Description of Model 1 Accuracy, Precision, and Recall scores.)
  - The balanced accuracy score for model 1 is .95. 
  - Logistic regression model predicts 100% with the `0` (healthy loan), a recall of 99%. 
  - It's 85% prediction on `1` (high-risk loan), a recall of 91%. 
  - Logistic regression model should be reevaluated although it has a very good scores, to see if there's overfitting. 

Machine Learning Model 2:(Description of Model 2 Accuracy, Precision, and Recall scores.)
   - The balanced accuracy score for model 2 is .99.
   - The logistic regression model, fit with oversampled data, predicts the `0` (healthy loan) with 100% precision, a recall of 99%. 
   - The `1` (high-risk loan) has a precision value of 100%, 99% for recall, this value of recall is higher than the original. 
   - Resampled data are more balanced or better fit. 

Summary: 
   Initial logistic regression model accuracy scores looks good. Logistic regression model recall improved on the high-risk loan on resampled data, accuracy score remains high. I would recommend the resampled logistic model as it has a good fit.
