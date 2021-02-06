# Credit_Risk_Analysis

## Overview of the analysis: 
**The purpose of this analysis is to apply machine learning to solve a real-world challenge: credit card risk.** Resampling Models, the SMOTEENN Algorithm, and Ensemble Classifiers were used to predict credit risk.

## Results: 
- For RandomOverSampler, the balanced accuracy scores and the precision and recall scores as seen below show an accuracy of 67.7%, a high precision in predicting low risk statuses, but the difference between the two recall scores is 0.17%.
![randomoversampler](resources/image1.PNG?raw=true "Title")

- For SMOTE, the balanced accuracy scores and the precision and recall scores as seen below show an accuracy of 66.2%, a high precision of 1.00 in predicting low risk statuses, but the difference between the two recall scores is 0.06%.
![smote](resources/image2.PNG?raw=true "Title")

- For ClusterCentroids, the balanced accuracy scores and the precision and recall scores as seen below show an accuracy of 54.4%, a high precision of 1.00 in predicting low risk statuses, but the difference between the two recall scores is 0.25%.
![cc](resources/image3.PNG?raw=true "Title")

- For SMOTEENN, the balanced accuracy scores and the precision and recall scores as seen below show an accuracy of 64.9%, a high precision of 1.00 in predicting low risk statuses, but the difference between the two recall scores is 0.11%.
![smoteenn](resources/image4.PNG?raw=true "Title")

- For BalancedRandomForestClassifier, the balanced accuracy scores and the precision and recall scores as seen below show an accuracy of 78.9%, a high precision of 1.00 in predicting low risk statuses and a slightly better precision of 0.03 in predicting high risk statuses as compared to the aforementioned models, but the difference between the two recall scores is 0.17%.
![brf](resources/image5.PNG?raw=true "Title")

- For EasyEnsembleClassifier, the balanced accuracy scores and the precision and recall scores as seen below show an accuracy of 93.2%, a high precision of 1.00 in predicting low risk statuses and a slightly better precision of 0.09 in predicting high risk statuses as compared to the aforementioned models, and the difference between the two recall scores is only 0.02%.
![eec](resources/image6.PNG?raw=true "Title")

## Summary: 

Based on the metrics of the models in scope of this analysis, it can be determined that the EasyEnsembleClassifier model is a good recommendation. The EasyEnsembleClassifier model shows relatively high recall scores of 92% and 94% and the highest precision of all the models at 0.09 for predicting high risk statuses and a precision of 1.00 for low risk statuses. The balanced accuracy score was also high at 93.2%. Precision and recall scores were able to determine a model's performance. All other models in scope of this analysis proved to be weak models to use for this analysis.  



