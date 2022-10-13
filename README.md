# Credit_Risk_Analysis

## Overview of the analysis: 
In this analysis we will be analyzing the credit card dataset from LendingClub and using machine learning and statistical reasoning to predict if a person is low risk or high risk for having a creit card. We will use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

## Purpose of Analysis

Results: Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.

## Results

Below are the Results from six machine learning models that that we ran along with the balanced accuracy scores, the precision and recall scores.

### Naive Random Oversampling
<img width="657" alt="Naive Random Oversampling" src="https://user-images.githubusercontent.com/107590196/195484410-3ac77b03-7459-4edc-ae75-8d612b2e6cd9.png">


      - Balanced accuracy scores: 0.6456130066757718
      - Precision: High Risk is low at 1 % and high for Low Risk
      - Recall scores: High risk is 61% / Low is 64%


### SMOTE Oversampling
<img width="739" alt="SMOTE Oversampling" src="https://user-images.githubusercontent.com/107590196/195483681-c827f742-92f9-492c-8207-dd3d4b591ac1.png">


      - Balanced accuracy scores: 0.6234433606890912
      - Precision: High Risk is low at 1 % and high for Low Risk
      - Recall scores: High risk is 61% / Low is 64%


### Undersampling - ClusterCentroids
<img width="750" alt="Undersampling - ClusterCentroids" src="https://user-images.githubusercontent.com/107590196/195483716-42eabe03-9789-4184-b716-0cb3d2351037.png">


      - Balanced accuracy scores: 0.6234433606890912
      - Precision: High Risk is low at 1 % and high for Low Risk
      - Recall scores: High risk is 61% / Low is 45%

### Combination (Over and Under) Sampling - SMOTEENN
<img width="713" alt="Combination (Over and Under) Sampling" src="https://user-images.githubusercontent.com/107590196/195483751-0958b00f-cff1-4521-9fe1-ca9467d8c3d6.png">


      - Balanced accuracy scores: 0.5293026900499977
      - Precision: High Risk is low at 1 % and high for Low Risk
      - Recall scores: High risk is 70% / Low is 58%


### Balanced Random Forest Classifier
<img width="732" alt="Balanced Random Forest Classifier" src="https://user-images.githubusercontent.com/107590196/195483774-f805098f-8de9-407e-9fd8-ae32be2e42d7.png">


      - Balanced accuracy scores: 0.7877672625306695
      - Precision: High Risk is low at 4 % and high for Low Risk
      - Recall scores: High risk is 67% / Low is 91%


### Easy Ensemble AdaBoost Classifier
<img width="739" alt="Easy Ensemble AdaBoost Classifier" src="https://user-images.githubusercontent.com/107590196/195483833-7b32b779-e707-4d45-8c06-8005b5a6aea8.png">



      - Balanced accuracy scores: 0.925427358175101
      - Precision: High Risk is low at 7 % and high for Low Risk
      - Recall scores: High risk is 91% / Low is 94%

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.
