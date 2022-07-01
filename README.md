# Credit_Risk_Analysis

## Overview: 

For this week we are using a data set from LendingClub to use supervised machine learning to determine an applicant’s credit risk.

To do this we used Random Over Sample and SMOTE algorithms to oversample, while then using cluster centroids to the under sample.  After this was completed, we then used both Balanced Random Forest Classifier and Easy Ensemble Classifier machine learning models to predict credit risk.


## Results:

   - Deliverable 1 Resampling Models to Predict Credit Risk:  By doing oversampling and undersampling algorithms we are able to use machine learning to generate a classification report.  Below is a breakdown of those methods and their results.

     - Naive Random Oversampling:  For the naive random sampling our accuracy score was 64% when rounding to the nearest hundreths place.  Our averaged out precision score on .99 and recall score .64 and finally our f1 score of .77.  See below image.

![This is an image](https://github.com/BMoreland20/Credit_Risk_Analysis/blob/main/Resources/naive_random_oversampling.png)

     - SMOTE Oversampling:  For the SMOTE over sampling method our accuracy score is 66% when rounding to the nearest hundreths place. Our averaged out precision score is .99, recal is .69, and f1 is .81.  See below image.

![This is an image](https://github.com/BMoreland20/Credit_Risk_Analysis/blob/main/Resources/SMOTE_oversampling.png)
     - Under sampling ClusterCentroids: When under sampling our accuracy score is 54% when rounding to the nearest hundreths.  Our average precision score is .99, our recall is .40, and our f1 score is .56. See below image.
 
![This is an image](https://github.com/BMoreland20/Credit_Risk_Analysis/blob/main/Resources/undersampling.png)


   - Deliverable 2 SMOTEENN Algorithm to Predict Credit Risk:  By using both under and over sampling methods we will use the SMOTEENN algorithm to resample the dataset and use the count on target classes, train a logistic regression classifier to generate a classification report.  Below is the breakdown of this method and its results

     - Over and Under Sampling:  When performing our analysis on the combined over and under sampling we can see that our accuracy score is 66%, our average prediction score is .99, our recolection is .69, and our f1 score is .81.  See below image.

![This is an image](https://github.com/BMoreland20/Credit_Risk_Analysis/blob/main/Resources/over_and_under_sampling.png)


   - Deliverable 3 Ensemble Classifiers to Predict Credit Risk:  For our last deliverable we used ensamble classifiers to predict credit risk.

     - Random Forest:  Our balanced random forest accuracy score comes to 79%, our combined prediction score is .99, our recall score is .87, and our f1 score is .93.  See below image.

![This is an image](https://github.com/BMoreland20/Credit_Risk_Analysis/blob/main/Resources/balanced_random_forest_classifier.png)

     - Easy Ensemble:  Our Easy Ensemble AdaBoost accuracy score is 93%, our combined prediction score is .99, our recolection score is 94, and our f1 score is .97.  See below image.

![This is an image](https://github.com/BMoreland20/Credit_Risk_Analysis/blob/main/Resources/easy_ensemble_adaboost_classifier.png)


## Summary:

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.
