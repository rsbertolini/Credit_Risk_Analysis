# Credit_Risk_Analysis

## Overview of the analysis
The purpose of this project was to compare several machine learning algorithms to predict credit risk.
* Deliverable 1 - We explored oversampling the data using RandomOverSampler and SMOTE algorithms and undersampled the data using ClusterCentroids algorithm.
* Deliverable 2 - We explored a combinatorial approach of over and undersampling using the SMOTEEN algorithm.
* Deliverable 3 - We explored 2 new machine learning models, BalancedRandomForestClassifier and EasyEnsembleClassifier, that reduce bias.

## Results
**RandomOverSampler**

![RandomOverSampler](/Images/RandomOverSampler.PNG)

* The credit risk accuracy score is 64%.
* The high risk precision score is only 1% and the low risk precision score is 100%.
* The high risk sensitivity score is 62% and the low risk sensitivity score is 65%.

**SMOTE**


![SMOTE](/Images/SMOTE.PNG)

* The credit risk accuracy score is 63%.
* The high risk precision score is only 1% and the low risk precision score is 100%.
* The high risk sensitivity score is 62% and the low risk sensitivity score is 64%.

**Cluster Centroids**


![ClusterCentroids](/Images/ClusterCentroids.PNG)

* The credit risk accuracy score is 51%.
* The high risk precision score is only 1% and the low risk precision score is 100%.
* The high risk sensitivity score is 59% and the low risk sensitivity score is 44%.

**SMOTEEN**


![SMOTEEN](/Images/SMOTEEN.PNG)

* The credit risk accuracy score is 64%.
* The high risk precision score is only 1% and the low risk precision score is 100%.
* The high risk sensitivity score is 70% and the low risk sensitivity score is 57%.

**BalancedRandomForestClassifier**


![BalancedRandomForestClassifier](/Images/BalancedRandomForestClassifier.PNG)

* The credit risk accuracy score is 79%.
* The high risk precision score is only 4% and the low risk precision score is 100%.
* The high risk sensitivity score is 67% and the low risk sensitivity score is 91%.

**EasyEnsembleClassifier**


![EasyEnsembleClassifier](/Images/EasyEnsembleClassifier.PNG)

* The credit risk accuracy score is 92%.
* The high risk precision score is 7% and the low risk precision score is 100%.
* The high risk sensitivity score is 91% and the low risk sensitivity score is 94%.

## Summary:
I would not recommend the lender to use these prediction algorithms.  All of the algorithms for high risk predictions had very low precision.  There was a lot of inaccuracy
around a large subset of applicants getting classified as high risk that were actually low risk so this presents a large missed opportunity for revenue.


