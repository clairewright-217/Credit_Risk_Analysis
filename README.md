# Credit_Risk_Analysis

## Overview


The purpose of this analysis was to determine which machine learning module would best be able to identify good loans versus risky loans based on a standard set of features about the loans. 

The six different modules tested to predict loan risk were the following:

1. RandomOverSampler
    - resample the data by oversampling, then train a logistic regression classifier with this new dataset
    - imbalanced-learn and scikit-learn libraries used
2. SMOTE
    - resample the data by oversampling, then train a logistic regression classifier with this new dataset
    - imbalanced-learn and scikit-learn libraries used
3. ClusterCentroids
    - resample the data by undersampling, then train a logistic regression classifier with this new dataset
    - imbalanced-learn and scikit-learn libraries used
4. SMOTEENN
    -  resample the data by using a combinatorial approach of over- and understampling, then train a logistic regression classifier with this new dataset
    - imbalanced-learn and scikit-learn libraries used
5. BalancedRandomForestClassifer
    - resample the dataset and then train this ensemble classifer on the sampled data
    - imblearn.esemble libary used
6. EasyEnsembleClassifer
    - resample the dataset and then train this ensemble classifer on the sampled data
    - imblearn.esemble libary used

Naive oversampling - hoorible precision, made a lot of false positives
these models work best with balanced datasets, so many 1s compared to zeros so doesnt predict zeros well

Smote - this doesnt help in improving model performance

## Results

1. RandomOverSampler

![RandomOverSampler](/Module-17-Challenge_Resources/Resources/RandomOverSampler_Results.png)



2. SMOTE

![SMOTE](/Module-17-Challenge_Resources/Resources/SMOTE_Results.png)

3. ClusterCentroids

![ClusterCentroids](/Module-17-Challenge_Resources/Resources/ClusterCentroids_Results.png)


4. SMOTEENN

![SMOTEENN](/Module-17-Challenge_Resources/Resources/SMOTEENN_Results.png)

5. BalancedRandomForestClassifer

![BalancedRandomForestClassifer(/Module-17-Challenge_ResourcesResources/BalRandomForestClassifer_Results.png)


6. EasyEnsembleClassifer

![EasyEnsembleClassifer](/Module-17-Challenge_Resources/Results/EasyEnsembleClassifer_Results.png)


## Summary
