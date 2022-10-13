# Credit_Risk_Analysis

## Overview of the analysis: 
In this analysis we will be analyzing the credit card dataset from LendingClub and using machine learning and statistical reasoning to predict if a person is low risk or high risk for having a creit card. We will use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

## Purpose of Analysis

Results: Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.

## Results

Below are the Results from six machine learning models that that we ran along with the balanced accuracy scores, the precision and recall scores.

### Naive Random Oversampling
<img width="748" alt="Naive Random Oversampling" src="https://user-images.githubusercontent.com/107590196/195483664-837bb4a9-93ec-49b0-98e1-e0bca8cbcafc.png">

      -balanced accuracy scores: 0.6456130066757718
      -precision
      -recall scores


### SMOTE Oversampling
<img width="739" alt="SMOTE Oversampling" src="https://user-images.githubusercontent.com/107590196/195483681-c827f742-92f9-492c-8207-dd3d4b591ac1.png">


      -balanced accuracy scores: 0.6234433606890912
      -precision
      -recall scores

### Undersampling - ClusterCentroids
<img width="750" alt="Undersampling - ClusterCentroids" src="https://user-images.githubusercontent.com/107590196/195483716-42eabe03-9789-4184-b716-0cb3d2351037.png">


      -balanced accuracy scores: 0.6234433606890912
      -precision
      -recall scores

### Combination (Over and Under) Sampling - SMOTEENN
<img width="713" alt="Combination (Over and Under) Sampling" src="https://user-images.githubusercontent.com/107590196/195483751-0958b00f-cff1-4521-9fe1-ca9467d8c3d6.png">


      -balanced accuracy scores: 0.5293026900499977
      -precision
      -recall scores

### Balanced Random Forest Classifier
<img width="732" alt="Balanced Random Forest Classifier" src="https://user-images.githubusercontent.com/107590196/195483774-f805098f-8de9-407e-9fd8-ae32be2e42d7.png">


      -balanced accuracy scores: 0.7877672625306695
      -precision
      -recall scores

### Easy Ensemble AdaBoost Classifier
<img width="739" alt="Easy Ensemble AdaBoost Classifier" src="https://user-images.githubusercontent.com/107590196/195483833-7b32b779-e707-4d45-8c06-8005b5a6aea8.png">



      -balanced accuracy scores: 0.925427358175101
      -precision
      -recall scores


## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.
