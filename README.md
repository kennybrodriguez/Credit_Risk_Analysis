# Credit_Risk_Analysis
Credit Risk Analysis models

## Overview
This project focused on utilizing different machine learning models to help classify credit card risk. The data used came for LendingClub, a peer to peer lending services company. The analysis focuses on using different techniques to train and evaluate models with unbalanced classes. Techniques used are RandomOverSampler, SMOTE algorithms, ClusterCentroids algorithm, over/undersampling using SMOTEEN, BalancedRandomForestClassifier, and EasyEnsembleClassifier

The value count of the loan_status column returns 68470 low risk loan applications in comparison to 347 high risk loan applications. Below are the results of different techniques to deal with unbalanced data.

## Results

* Using RandomOverSampler we were able to reach a 66% accuracy score. Precision was 99.7% and recall was 60%. 

![Results](/Resources/credit1.PNG)

* Using SMOTE algorithm, we were able to reach a 65.8% accuracy score. Precision was 99% and recall was 69%. 

![Results](/Resources/credit2.PNG)

* Using ClusterCentroids algorithm, we were able to reach a 54% accuracy score. Precision was 99% and recall was 40%. 

![Results](/Resources/credit3.PNG)

* Using SMOTEEN algorithm, we were able to reach a 65% accuracy score. Precision was 99% and recall was 57%. 

![Results](/Resources/credit4.PNG)

* Using BalancedRandomForestClassifier, we were able to reach a 79% accuracy score. Precision was 99% and recall was 87%. 

![Results](/Resources/credit5.PNG)

* Using EasyEnsembleClassifier, we were able to reach a 92% accuracy score. Precision was 99% and recall was 95%. 

![Results](/Resources/credit6.PNG)

## Summary
Overall, these are different methods in dealing with unbalanced data. Using different techniques in regards to resampling the data and running different machine learning models helped show their effectiveness in regards to their accuracy, precision, and recall. 

Using the results provided, I would recommend utilizing the EasyEnsembleClassifier as it acheived the highest scores in regards to accuracy, precision and recall. In regards to the loan application data I would recommend a model with a higher sensitivity score to have fewer false negatives.

