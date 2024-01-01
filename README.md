# Module-12-Credit-Risk-Resampling
# Credit Risk Analysis Report

## Overview

The purpose of this analysis is to evaluate the performance of two machine learning models in predicting credit risk. The models are trained on both the original and resampled datasets to assess whether resampling techniques, specifically random under-sampling, can improve the model's ability to handle imbalanced data.

## Results

### Original Dataset Model

- Balanced Accuracy Score: 95.2%
- F1 Score: 99%
- Precision Score:
  - Precision for Healthy Loan: 99.7%
  - Precision for High-Risk Loan: 84.8%
- Recall Score:
  - Recall for Healthy Loan: 99.5%
  - Recall for High-Risk Loan:90.9%

### Resampled Dataset Model

- Balanced Accuracy Score: 99.3%
- F1 Score: 99%
- Precision Score:
  - Precision for Healthy Loan:99.9%
  - Precision for High-Risk Loan: 84.1%
- Recall Score:
  - Recall for Healthy Loan: 99.3%
  - Recall for High-Risk Loan: 99.3%

## Summary

The analysis indicates that the resampled dataset model performs differently compared to the original dataset model. The balanced accuracy score,f1 score, precision, and recall scores vary between the two models. The resampled dataset model may be more suitable for scenarios where addressing imbalanced classes is crucial.

Considering the specific goals and constraints of the credit risk prediction task, it is recommended to choose the model based on the desired balance between precision and recall. If identifying high-risk credit applications is a priority, the resampled dataset model might be preferred, as it shows improvements in recall for high-risk cases. However, if precision is of utmost importance to avoid false positives, the original dataset model might be considered.

In conclusion, the choice between the original and resampled dataset models depends on the business objectives and the trade-off between correctly identifying high-risk cases and minimizing false positives.

