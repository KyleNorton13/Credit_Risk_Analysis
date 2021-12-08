# Credit_Risk_Analysis

## Overview of the analysis

### Overview of loan prediction analysis

The objective of this analysis was to use different techniques to to evaluate the performance of different credit risk models. Jill's instructions were to use imbalanced-learn and scikit-learn libraries in order to put together our analysis. Using the algorithims such as random over sampler and SMOTE for oversampling, cluster centroids for undersampling I was able to evaluate the performance of each of the models. The next two mdoels we used were balanced random forest classifier and easy ensemble classifier as these two assist in reducing bias. Each of the techniques, alogrithims, and models were used to predict the credit risk of the data provided to which we then make our evaluations as to which had a successful performance. 

## Results

### Over Sampling

- Random Over Sampler

![image](https://user-images.githubusercontent.com/87450415/145142271-328e2688-b18c-481e-bcc1-84e4910f199c.png)

- SMOTE

![image](https://user-images.githubusercontent.com/87450415/145143474-ff76eb4f-785b-4068-9f10-4bc19cd510dc.png)

### Under Sampling

- Cluster Centroids

![image](https://user-images.githubusercontent.com/87450415/145143546-24bb536b-ab3d-40e3-97fb-e7b16b62d219.png)

### Combination

- SMOTEENN

![image](https://user-images.githubusercontent.com/87450415/145143641-aec8be38-05f1-4678-9e26-14438445d6d4.png)

### ENSEMBLE 

- Balanced Random Forest Classifier

![image](https://user-images.githubusercontent.com/87450415/145143745-e6ed1046-1b59-4aa9-8adb-09c6cd26c63b.png)

- Easy Ensemble Classifier

![image](https://user-images.githubusercontent.com/87450415/145143809-e8d9d212-6a19-45ee-8c04-622fcb801702.png)


## SUMMARY

The results of this analysis determined that the most accurate machine learning model was easy ensemble classifier. This model posted an accuracy socre of 93.17% and was by far the leader in accuracy. The models within the credit_risk_resampling notebook which were, random oversampling, SMOTE oversampling, cluster centroids, and SMOTEENN (combination), all were the bottom 4 in terms of accuracy. The top two accuracy scores were from the ensemble classifiers balanced random forest classifer and easy ensemble classifier, posting 
accuracy scores of 78.85% and 93.17% respectively. This was to be expected as both of the ensemble classifiers aid in reducing bias within the model which in turn increases its accuracy. The screenshots of the balanced accuracy score, confusion matrix, and classification reports are seen below. 
















