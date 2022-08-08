# Credit Risk Analysis

## Overview

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Using a dataset from LendingClub, a peer-to-peer lending services company, we are to determine the best ways to train our model and predict credit risk.

## Results

- Using Naive Random Oversampling
  - The accuracy score was .64
  - The precision score was .01
  - The recall score was .72
  
![image](https://user-images.githubusercontent.com/103209236/183516411-dc031812-6293-442c-b5ac-d2f0ffd07aa0.png)

- Using SMOTE Oversampling
  - The accuracy score was .66
  - The precision score was .01
  - The recall score was .62
  
![image](https://user-images.githubusercontent.com/103209236/183516549-c75564b7-5e13-45df-8431-551ad240de82.png)

- Using Undersampling
  - The accuracy score was .54
  - The precision score was .01
  - The recall score was .69
  
![image](https://user-images.githubusercontent.com/103209236/183516690-6d4440f0-cfef-47f5-9f0c-745f538bfa87.png)

- Using Combination (Over and Under) Sampling
  - The accuracy score was .67
  - The precision score was .01
  - The recall score was .73
  
![image](https://user-images.githubusercontent.com/103209236/183516876-ac000d46-fb05-4019-887b-c3b680354b72.png)

- Using a Balanced Forrest Classifier Model
  - The accuracy score was .79
  - The precision score was .03
  - The recall score was .70
  
![image](https://user-images.githubusercontent.com/103209236/183517072-326e59f6-98f3-4d50-95a2-3b2ff0c8be2d.png)

- Using Easy Ensemble AdaBoost Classifier
  - The accuracy score was .93
  - The precision score was .09
  - The recall score was .92
  
![image](https://user-images.githubusercontent.com/103209236/183517274-742f8c0b-c991-4797-8b50-a6fbb1645047.png)

## Summary

Utilizing the Easy Ensemble AdaBoost Classifier, we were able to get an accuracy score above .90 (far and away the best of the six models). The precision on all six models was below .10. The Easy Ensemble AdaBoost Classifier also had the highest recall score at .92, the only score above .90. I would recommend the Easy Ensemble AdaBoost Classifier for determining credit risk in the future.
