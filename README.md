# Credit Risk Supervised Learning Model Analysis

## Overview of the Analysis

The purpose of this analysis was to determine the risk in approving loans based on seven relevant factors; the size of the loan and the interest rate, the income of the borrower as well as their debt to income ratio, the number of accounts and derogatory marks, and their total debt. These factors were analyzed with the goal of predicting whether a loan would be healthy or high-risk.

The first step in establishing the model was to separate the data into labels and features, or the output variable to be predicted and the properties used to determine that.

Next was to split the data into training and testing groups. The larger training group allows the model to learn the relationships and the smaller testing group assesses the model's ability to predict outcomes.

Then to fit the logistic regression model, which divides the input into groups based on a probability estimate determined by a particular threshold.

Finally, to showcase the results, a confusion matrix was generated providing the numbers of true positives, true negatives, false positives and false negatives. A classification report was also generated to provide information on the effectiveness of the model. 

## Results

* Supervised Credit Risk Machine Learning Model:
    * The model predicted that there were significantly more healthy loans than high-risk loans.
    * The model's accuracy was very high, at 0.99.
    * The model predicted healthy loans with perfect precision and recall.
    * The model predicted high-risk loans with 0.87 precision and 0.95 recall, indicating less accuracy of the positive predictions and nearly perfect ability to identify actual positives.

## Summary

Ultimately, these results indicate very good model reliability, particularly for healthy loans. 
I would be comfortable recommending this model to predict loan risk based on the high recall score for both loan labels. High recall can help prevent financial loss due to mistakenly approving high risk loans.
