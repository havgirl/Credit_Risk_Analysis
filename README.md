# Credit_Risk_Analysis

## Overview
The purpose of this challenge is to apply our machine learning skills to help sovle a real-world challenge: credit card risk.  By employing different techniques to train and evaluate models with umblanced classes we will develop a final recommendation on which, if any, models are the best for future use.

## Machine Learning Model Results

### Naive Random Oversampling

![](Images/Naive_Random_Oversampling_Imbalanced_Classifcation_Report.png)

- Balanced Accuracy: ![](Images/Naive_Random_Oversampling_Balanced_Accuracy_Score.png)
- High-risk loan precision: low - 0.01
- Low-risk loan precision: high - 1.00
- High-risk loan recall: .66
- Low-risk loan precission: .67

### SMOTE Oversampling

![](Images/SMOTE_Oversampling_Imbalanced_Classifcation_Report.png)

- Balanced Accuracy: ![](Images/SMOTE_Oversampling_Balanced_Accuracy_Score.png)
- High-risk loan precision: low - 0.01
- Low-risk loan precision: high - 1.00
- High-risk loan recall: .62
- Low-risk loan precission: .64

### Undersampling

![](Images/Cluster_Centroids_Undersampling_Imbalanced_Classifcation_Report.png)

- Balanced Accuracy: ![](Images/Cluster_Centroids_Undersampling_Balanced_Accuracy_Score.png)
- High-risk loan precision: low - 0.01
- Low-risk loan precision: high - 1.00
- High-risk loan recall: .63
- Low-risk loan precission: .40

### Combination OverUnder Sampling

![](Images/SMOTE_Combination_OverUnder_Sampling_Imbalanced_Classifcation_Report.png)

- Balanced Accuracy: ![](Images/SMOTE_Combination_OverUnder_Sampling_Balanced_Accuracy_Score.png)
- High-risk loan precision: low - 0.01
- Low-risk loan precision: high - 1.00
- High-risk loan recall: .70
- Low-risk loan precission: .57

### Balanced Random Forest Classifier

![](Images/Balanced_Random_Forest_Classifier_Imbalanced_Classification_Report.png)

- Balanced Accuracy: ![](Images/Balanced_Random_Forest_Classifier_Balanced_Accuracy_Score.png)
- High-risk loan precision: low - 0.07
- Low-risk loan precision: high - 1.00
- High-risk loan recall: .63
- Low-risk loan precission: .40

### Easy Ensemble AdaBoost Classifier

![](Images/Easy_Ensamble_AdaBoost_Classifier_Imbalanced_Classification_Report.png)

- Balanced Accuracy: ![](Images/Easy_Ensamble_AdaBoost_Classifier_Balanced_Accuracy_Score.png)
- High-risk loan precision: low - 0.04
- Low-risk loan precision: high - 1.00
- High-risk loan recall: .67
- Low-risk loan precission: .91

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning
There is a recommendation on which model to use, or there is no recommendation with a justification
