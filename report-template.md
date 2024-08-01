# Module 12 Report Template

## Overview of the Analysis

The goal of this analysis was to create and evaluate a machine learning model designed to assess credit risk for loan applications. By employing logistic regression, the model aims to determine whether a loan should be classified as a healthy loan (0) or a high-risk loan (1), based on a range of financial and personal factors related to the applicants. This model has the potential to aid the company in making more informed lending decisions and managing risk effectively.

Model Performance Metrics
-Accuracy: 0.99
The model achieved a 99% accuracy rate, correctly predicting the loan status in almost all cases from the test set.

Precision:

-Healthy loans (0): 1.00
The model perfectly identifies healthy loans with no false positives.
-High-risk loans (1): 0.87
The model has a high precision for high-risk loans, accurately identifying them 87% of the time.

Recall:

-Healthy loans (0): 1.00
The model effectively identifies all healthy loans with no false negatives.
-High-risk loans (1): 0.89
The model captures 89% of all actual high-risk loans in the dataset.

F1-score:

-Healthy loans (0): 1.00
The F1-score is perfect for healthy loans, indicating a perfect balance of precision and recall.
-High-risk loans (1): 0.88
The F1-score for high-risk loans reflects a strong balance of precision and recall.

## Summary and Recommendation
The logistic regression model demonstrates exceptional performance in classifying both healthy and high-risk loans. With an impressive accuracy of 99%, the model delivers highly reliable predictions for most cases.

Healthy Loans: The model exhibits flawless precision, recall, and F1-score (all 1.00), indicating it accurately identifies every healthy loan without error.
High-Risk Loans: While the model performs admirably, it is not without limitations. It has a precision of 0.87, correctly identifying high-risk loans 87% of the time, and a recall of 0.89, capturing 89% of all actual high-risk loans.
Based on these results, I strongly recommend adopting this model for credit risk assessment. The strengths of the model include:

Exceptional overall accuracy
Flawless prediction of healthy loans
Strong identification of high-risk loans
The model’s capability to accurately identify healthy loans is particularly advantageous, allowing the company to confidently approve low-risk applications. Although the high-risk loan identification is not perfect, it significantly improves over random guessing and serves as a valuable tool for flagging potentially risky applications for additional scrutiny.
