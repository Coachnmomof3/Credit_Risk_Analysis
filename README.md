# Credit_Risk_Analysis

## Overview of the analysis:

The purpose of this analysis it to employ different techniques to train and evaluate models with unbalanced classes. Jill request that I use imbalanced and scikit learning libraries to bulild and evaluate models using resampling. Using the data set provided from LendingClub and other lending service companies we will be under and over sampled.  I will compare two new machine learning models that reduce bias to precict credit risk. From this I am expected to recomend if the models should be use to predict credit risk.  

## Results: 
### Summary of the machine learning models
![Summary](https://github.com/Coachnmomof3/Credit_Risk_Analysis/blob/main/Summary%20of%20the%20machine%20learning%20models.png)

* ### Oversampling Naive Random
    * Accuracy_score= .66
    * Precision= .99
    * Recall= .58

* ### Oversampling Smote
    * Accuracy_score= .65
    * Precision= .99
    * Recall= .68

* ### Undersampling ClusterCentroids
    * Accuracy_score= .55
    * Precision= .99
    * Recall= .41

* ### Balanced Random Forest Classifier
    * Accuracy_score= .79
    * Precision= .99
    * Recall= .87

* ### Over and Under SMOTEENN
    * Accuracy_score= .64
    * Precision= .99
    * Recall= .57

* ### Easy Ensemble AdaBoost Classifier
    * Accuracy_score= .93
    * Precision= .99
    * Recall= .87

## Summary: 

We can see from the above image that the best model is one that was created to predict the unbalanced classification problem of credit risk, the Ensemble AdaBoost Classifier. We also see the Balanced Random Forest Classifier do well with a high recall and accuracy score. I would recommend the Ensemble AdaBoost Classifier due to its higher overall scores for a classification prediction being near 1 which is what we want in this prediction.
