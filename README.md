# Credit_Risk_Analysis
module 17-supervised machine learning 
## Overview:
Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, different techniques used to train and evaluate models with unbalanced classes. Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, the data is oversampleed using the RandomOverSampler and SMOTE algorithms, and undersampled using the ClusterCentroids algorithm. Also, a combinatorial approach of over and undersampling using the SMOTEENN algorithm was used. Next,two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk were modeled. finally, evaluated the performance of these models and make a recommendation on whether they should be used to predict credit risk.
## Result:
### Oversampling Report:
- Below image shows the Oversampling report with balanced accuracy score and imbalanced classification report.
  ![Oversampling_report](https://user-images.githubusercontent.com/92752935/156888733-3c212069-a687-4e5d-bc08-2e2a797a895f.png)
### SMOTE Oversampling Report:
- Below image shows the SMOTE oversampling report with balanced accuracy score and imbalanced classification report.
  ![SMOTE_oversampling_report](https://user-images.githubusercontent.com/92752935/156888802-2606e469-cb09-454c-aeaa-b55c13886829.png)
### Undersampling Report:
- Below image shows the undersampling report with balanced accuracy score and imbalanced classification report.
  ![Undersampling_report](https://user-images.githubusercontent.com/92752935/156888852-e2f2d001-f451-413e-aaea-cd6b20e3e574.png)
### Combination Sampling Report:
- Below image shows the combination sampling report with balanced accuracy score and imbalanced classification report.
   ![Combination_sampling_report](https://user-images.githubusercontent.com/92752935/156888890-29fe27f9-0dc8-4dd0-8ba7-53c3ddd8cbf4.png)
### Balanced Random Forrest classifier Report:
- Below image shows the Balanced Random Forrest classifier report with balanced accuracy score and imbalanced classification report.
  ![Balanced_random_forrest_report](https://user-images.githubusercontent.com/92752935/156888945-b59ee96d-a295-47ec-bcf4-c27789c5b208.png)
### Easy Ensemble classifier Report:
- Below image shows the Easy Ensemble classifier report with balanced accuracy score and imbalanced classification report.
  ![Easy_Ensemble_classifier_report](https://user-images.githubusercontent.com/92752935/156889024-18f6b6ae-76cf-4f5e-b504-7aef40ee0d8e.png)

## Summary:
- After evaluating different models, it is evident that combination sampling has more percentage of balanced accuracy score (64.8%) than other sampling models (around 54%).
- However the Easy ensemble classifier model yielded more balanced accuracy score (93.6%) than balanced random forrest classifier report (79.26%). Yet both these classifiaction     models yielded better accuracy score than sampling models.
- Combination sampling has sensitivity about 72% which is better than any other sampling models. Oversampling model sensitivity is closer (about 71%).
- Overall combination sampling model is better in predicting than other sampling models but the classifier models gave much better results in predicting credit risk.
