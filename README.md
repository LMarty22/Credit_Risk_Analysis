# Credit_Risk_Analysis

## Overview of the analysis: Explain the purpose of this analysis.

The purpose of this analysis is to use machine learning in order to predict credit risk. By training and evaluating the model using different methods such as RandomOverSampler, SMOTE, ClusterCentroids and SMOTEENN. Using the data provided each of the different methods of analysis will be tested to see which is most accurate at predicting credit risk.

## Results:

#### Naive Random Oversampling

Accuracy Score

![Accuracy Score](https://github.com/LMarty22/Credit_Risk_Analysis/blob/main/Images/1_NaiveRandomOverSampler_Accuracy.png)

Precision Score

![Precision Score](https://github.com/LMarty22/Credit_Risk_Analysis/blob/main/Images/1_NaiveRandomOverSampler_Precision.png)

#### SMOTE Oversampling

Accuracy Score

!["Accuracy Score"](https://github.com/LMarty22/Credit_Risk_Analysis/blob/main/Images/2_Smote_Accuracy.png)

Precision Score

![Precision Score](https://github.com/LMarty22/Credit_Risk_Analysis/blob/main/Images/2_Smote_Precision.png)

#### Cluster Centroids Undersampling

Accuracy Score

![Accuracy Score](https://github.com/LMarty22/Credit_Risk_Analysis/blob/main/Images/3_ClusterCentroid_Accuracy.png)

Precision Score

![Precision Score](https://github.com/LMarty22/Credit_Risk_Analysis/blob/main/Images/3_ClusterCentroid_Precision.png)

#### SMOTEENN

Accuracy Score

![Accuracy Score](https://github.com/LMarty22/Credit_Risk_Analysis/blob/main/Images/4_SMOTEENN_Accuracy.png)

Precision Score

![Precision Score](https://github.com/LMarty22/Credit_Risk_Analysis/blob/main/Images/4_SMOTEENN_Precision.png)

#### BalancedRandomForestClassifier

Accuracy Score

![Accuracy Score](https://github.com/LMarty22/Credit_Risk_Analysis/blob/main/Images/5_Random_Forest_Accuracy.png)

Precision Score

![Precision Score](https://github.com/LMarty22/Credit_Risk_Analysis/blob/main/Images/5_Random_Forest_Precision.png)


#### EasyEnsembleClassifier

Accuracy Score

![Accuracy Score](https://github.com/LMarty22/Credit_Risk_Analysis/blob/main/Images/6_Ensemble_Accuracy.png)

Precision Score

![Precision Score](https://github.com/LMarty22/Credit_Risk_Analysis/blob/main/Images/6_Ensemble_Presicion.png)



## Summary: 
Upon completion of analysis on the six techniques of analyzing credit risk, Easy Ensemble Classifier has proven to have the best accuracy for this set of data. EasyEnsemble method also has the highest precision, recall, and F1 scores as seen in the imbalanced classification reports created for each model. 

If a single model was to be selected to evaluate credit risk, the Easy Ensemble Classifier would be the best to use out of the six models which were analyzed. Although this model appears to have the highest accuracy score, it also indicates a .09 precision for high risk data, indicating that this model does not best at identifying the high risk applicants accurate all of the time. With this indication there will be applications noted as high risk, false positive. This model is a good start in building a model to identify credit risk for LendingClub company, however it can benefit from further training and analysis to improve the precision and accuracy of the model. 

