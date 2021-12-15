# Credit_Risk_Analysis
Apply machine learning to solve a real-world challenge: Credit Card Risk.

## Project Overview

In this project we have applied **Supervised Machine Learning** alogthrims to determine credit card risk. It is in the best interest of financial institutions, banks, and peer-to-peer lending firms to automate and improve the accuracy of detecting high-risk individuals, prior to granting loans to assure minimal default. In this project we have used several Machine Learning models and algorithms to predict the credit risk for issuing loans :

1. Imbalanced-learn
2. Scikit-learn
3. RandomOverSampler
4. SMOTE algorithms
5. ClusterCentroids algorithm
6. SMOTEENN algorithm
7. BalancedRandomForestClassifier (bias reduction model)
8. EasyEnsembleClassifier (bias reduction model)

## Purpose

The purpose of the project is to :

1. Explain how a machine learning algorithm is used in data analytics.
2. Create training and test groups from a given data set.
3. Implement the logistic regression, decision tree, random forest, and support vector machine algorithms.
4. Predict the results of the logistic regression, decision tree, random forest, and support vector machine algorithms.
5. Compare the advantages and disadvantages of each supervised learning algorithm.
6. Determine which supervised learning algorithm is best used for a given data set or scenario.
7. Use ensemble and resampling techniques to improve model performance.

## Results

We have used 6 Machine Learning Models to predict the credit card risk :

## 1. Naive Random Oversampling

<img width="650" alt="1" src="https://user-images.githubusercontent.com/88418201/146261481-b2f4c803-5a81-4d70-8889-1774daac9921.png">

1. Balanced Accuracy Score: 0.6497536370265621
2. Precision: The precision is low for high-risk loans (0.01) and high for low-risk loans (1.00)
3. Recall: High-risk (0.62) and Low-risk (0.68)

## 2. SMOTE Oversampling

<img width="650" alt="2" src="https://user-images.githubusercontent.com/88418201/146262767-3a19fe90-5f1b-4430-8c1c-0b573cc6922b.png">

1. Balanced Accuracy Score: 0.6443721269403855
2. Precision: The precision is low for high-risk loans (0.01) and high for low-risk loans (1.00)
3. Recall: High-risk (0.63) and Low-risk (0.66)

## 3. Undersampling

<img width="650" alt="3" src="https://user-images.githubusercontent.com/88418201/146263041-afa4dd3b-8e43-4e16-919b-88b5986af29d.png">

1. Balanced Accuracy Score: 0.6443721269403855
2. Precision: The precision is low for high-risk loans (0.01) and high for low-risk loans (1.00)
3. Recall: High-risk (0.60) and Low-risk (0.43)

## 4. Combination Over and Under Sampling

<img width="650" alt="4" src="https://user-images.githubusercontent.com/88418201/146263247-2e62f265-fd1a-45fe-8914-8810ee0cb88f.png">

1. Balanced Accuracy Score: 0.5158151733807124
2. Precision: The precision is low for high-risk loans (0.01) and high for low-risk loans (1.00)
3. Recall: High-risk (0.71) and Low-risk (0.56)

## 5. Balanced Random Forest Classifier

<img width="650" alt="5" src="https://user-images.githubusercontent.com/88418201/146263412-68618cb8-7485-47bf-be9a-64655de9c4b6.png">

1. Balanced Accuracy Score: 0.7877672625306695
2. Precision: The precision is low for high-risk loans (0.04) and high for low-risk loans (1.00)
3. Recall: High-risk (0.67) and Low-risk (0.91)

## 6. Easy Ensemble AdaBoost Classifier

<img width="650" alt="6" src="https://user-images.githubusercontent.com/88418201/146263572-ce7fbeb2-d2ff-4141-928a-31cb8459090d.png">

1. Balanced Accuracy Score: 0.925427358175101
2. Precision: The precision is low for high-risk loans (0.07) and high for low-risk loans (1.00)
3. Recall: High-risk (0.91) and Low-risk (0.94)

## Summary

When working with balanced accuracy, the highest compared accuracy between 0 and 1 and is closest to 1 is the best machine learning model. For the credit card data set, the Easy Ensemble AdaBoost Classifier is the best model to choose with its 0.92 balanced accuracy. The other models were below 0.80 balanced accuracy. The precision for all models were similar and within an appropriate range. The recall score also needs to fall within 0 and 1, with numbers closer to 1 being the better model. The Easy Ensemble AdaBoost Classifier had the highest recall score, making it the final best machine learning model to choose for further credit card analysis.


