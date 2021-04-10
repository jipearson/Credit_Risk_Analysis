# Credit_Risk_Analysis
![](images/lending.PNG)


## Analysis Overview

### Apply machine learning to solve a real-world challenge: credit card risk.
Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. We need to employ different techniques to train and evaluate models with unbalanced classes. We will use the imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.
<br><br>
Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, we oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, we use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, we compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. 
<br>

## Analysis Results

### RandomOverSampler 

- Balanced accuracy score: 64.94%
- Confustion Matrix:<br>![](images/RandomOverSampler_confusion.PNG)
- Classification Report <br>![](images/RandomOverSampler.PNG)


### SMOTE
- Balanced accuracy score: 65.84%
- Confustion Matrix:<br>![](images/SMOTE_confusion.PNG)
- Classification Report <br>![](images/SMOTE.PNG)


### ClusterCentroids
- Balanced accuracy score: 54.42%
- Confustion Matrix:<br>![](images/ClusterCentroids_confusion.PNG)
- Classification Report <br>![](images/ClusterCentroids.PNG)


### SMOTEENN
- Balanced accuracy score: 66.22%
- Confustion Matrix:<br>![](images/SMOTEENN_confusion.PNG)
- Classification Report <br>![](images/SMOTEENN.PNG)


### BalancedRandomForestClassifier
- Balanced accuracy score: 78.85%
- Confustion Matrix:<br>![](images/BalancedRandomForestClassifier_confusion.PNG)
- Classification Report <br>![](images/BalancedRandomForestClassifier.PNG)


### EasyEnsembleClassifier
- Balanced accuracy score: 93.17%
- Confustion Matrix:<br>![](images/EasyEnsembleClassifier_confusion.PNG)
- Classification Report <br>![](images/EasyEnsembleClassifier.PNG)


## Analysis Results