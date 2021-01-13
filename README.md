# Credit_Risk_Analysis

## Overview of the analysis:

The purpose of this analysis it to employ different techniques to train and evaluate models with unbalanced classes. Jill request that I use imbalanced and scikit learning libraries to bulild and evaluate models using resampling. Using the data set provided from LendingClub and other lending service companies we will be under and over sampled.  I will compare two new machine learning models that reduce bias to precict credit risk. From this I am expected to recomend if the models should be use to predict credit risk.  

## Results: 

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

## Summary: Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.
We can see from the above image that the best results were obtained by the Easy Ensemble AdaBoost Classifier. It is important to consider that when lending money, misclassifying a high-risk could result in the lost of the funds,  . 

The risk of lose steming from a misclassified high-risk should be looking for a model that has precision over a defined limit. The over all goal was to get the best out come that will minimize loss and maximize gain. If the company is willing to take .07 loss then the best model is the Easy Ensemble AdaBoost Classifier. Due to the models not having a .99 or higher outcome I would not suggest using any of the models shown above.
