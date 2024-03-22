# Analysis and Prediction of Cardiovascular Risk Using Supervised and Ensemble ML Models.

Prediction of Cardiovascular Risk using Supervised and Unsupervised Machine Learning Models.

![cvd](https://user-images.githubusercontent.com/115907457/221461207-fc3ba180-41f8-497d-911e-e4a02493a701.jpg)

## Task

The goal is to predict cardiovascular disease risk using the features/predictors in the dataset. The predictors in the dataset for this project are discrete and the outcome is binary, determining if the patient is at risk of being diagnosed with a cardiovascular disease or not.

This is a classification problem and so for this task, several different machine learning classification methods, was chosen and used to fit functions to predict the class of new data points. To improve the accuracies of all my model, I tuned the hyperparameters and evaluated the best parameters for each model. 

## Dataset Description
Source: 
(https://www.kaggle.com/datasets/sulianova/cardiovascular-disease-dataset)
All of the dataset values were collected during patient encounter. The number of data points in the dataset are 70,000, with 12 features.

## Result

### Performance for Gaussian Naive Bayes classifier
### Training:
AUC:0.729

accuracy:0.665

recall:0.527

precision:0.712

specificity:0.796
 
### Test:
AUC:0.721

accuracy:0.660

recall:0.514

precision:0.710

specificity:0.799

### Performance Logistic Regression classifier
### Training:
AUC:0.750

accuracy:0.688

recall:0.620

precision:0.705

specificity:0.752
 
### Test:
AUC:0.743

accuracy:0.682

recall:0.610

precision:0.701

specificity:0.751

LogisticRegression best parameters = {'C': 10, 'penalty': 'l2'}


### Performance for Random Forrest classifier
### Training:
AUC:0.748

accuracy:0.686

recall:0.628

precision:0.699

specificity:0.741
 
### Test:
AUC:0.743

accuracy:0.685

recall:0.622

precision:0.700

specificity:0.745

RandomForest best parameters = {'criterion': 'gini', 'max_depth': 4, 'max_features': 'auto', 'min_samples_split': 2, 'n_estimators': 15}


## Dependencies

Python

SKLearn

Numpy

Pandas

Seasborn

Matplotlib

![cvdai](https://user-images.githubusercontent.com/115907457/221463127-844837d5-ff3b-4966-a1da-09e47e0aa8de.png)

