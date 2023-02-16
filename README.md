# Credit_Risk_Analysis

## Overview
The purpose of this challenge is to apply our machine learning skills to help sovle a real-world challenge: credit card risk.  By employing different techniques to train and evaluate models with umblanced classes we will develop a final recommendation on which, if any, models are the best for future use.

## Machine Learning Model Results

### Naive Random Oversampling

![](Images/Naive_Random_Oversampling_Imbalanced_Classifcation_Report.png)

- Balanced Accuracy: ![](Images/Naive_Random_Oversampling_Balanced_Accuracy_Score.png)
- High-risk loan precision: low - 0.01
- Low-risk loan precision: high - 1.00
- High-risk loan recall: .62
- Low-risk loan precission: .65

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
- High-risk loan recall: .60
- Low-risk loan precission: .43

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
- High-risk loan precision: low - 0.04
- Low-risk loan precision: high - 1.00
- High-risk loan recall: .67
- Low-risk loan precission: .91

### Easy Ensemble AdaBoost Classifier

![](Images/Easy_Ensamble_AdaBoost_Classifier_Imbalanced_Classification_Report.png)

- Balanced Accuracy: ![](Images/Easy_Ensamble_AdaBoost_Classifier_Balanced_Accuracy_Score.png)
- High-risk loan precision: low - 0.07
- Low-risk loan precision: high - 1.00
- High-risk loan recall: .91
- Low-risk loan precission: .94

## Summary
In summary, when selecting a machine learning model it is best to select a model with accuracy closest to 1. For the credit card data set, the recommendation would be to use the Easy Ensemble AdaBoost Classifier - as this model had the highest balanced accuracy (.9254)

