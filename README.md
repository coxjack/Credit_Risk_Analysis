# Credit_Risk_Analysis
Challenge 17 for Butler Data Science

## Analysis 
Several machine learning models were used to analyze and  predict credit risk.

The following methods were used to analyze the data:
- Oversample the data using the **RandomOverSampler** and **SMOTE** methods.
- Undersample the data using the **ClusterCentroids** method.
- Use a combination of over and undersampling by using the **SMOTEENN** method.
- Two machine learning models were compared the **BalancedRandomForestClassifier** and **EasyEnsembleClassifier** methods -- these methods are used to reduce bias in sampling.

## Results

RandomOverSampler Accuracy Score:

![ROSacc](https://github.com/coxjack/Credit_Risk_Analysis/blob/main/Additional%20Images/ROS_accscore.png)

RandomOverSampler Confusion Matrix:

![ROScm](https://github.com/coxjack/Credit_Risk_Analysis/blob/main/Additional%20Images/ROS_cm.png)

RandomOverSampler Classification Report:

![ROScr](https://github.com/coxjack/Credit_Risk_Analysis/blob/main/Additional%20Images/ROS_classreport.png)

- The balanced accuracy score is 56%.
- The high_risk precision is about 1% with a 62% recall score.
- The low_risk population has a precision of 100% with a recall score of 68%

SMOTE Accuracy Score:

![SMOTEacc](https://github.com/coxjack/Credit_Risk_Analysis/blob/main/Additional%20Images/SMOTE_accscore.png)

SMOTE Confusion Matrix:

![SMOTEcm](https://github.com/coxjack/Credit_Risk_Analysis/blob/main/Additional%20Images/SMOTE_cm.png)

SMOTE Classification Report:

![SMOTEcr](https://github.com/coxjack/Credit_Risk_Analysis/blob/main/Additional%20Images/SMOTE_classreport.png)

- The balanced accuracy score is 64%.
- The high_risk precision is about 1% with a 63% recall score.
- The low_risk population has a precision of 100% with a recall score of 66%

ClusterCentroids Accuracy Score:

![ClusterCentroidsacc](https://github.com/coxjack/Credit_Risk_Analysis/blob/main/Additional%20Images/ClusterCentroids_accscore.png)

ClusterCentroids Confusion Matrix:

![ClusterCentroidscm](https://github.com/coxjack/Credit_Risk_Analysis/blob/main/Additional%20Images/ClusterCentroids_cm.png)

ClusterCentroids Classification Report:

![ClusterCentroidscr](https://github.com/coxjack/Credit_Risk_Analysis/blob/main/Additional%20Images/ClusterCentroids_classreport.png)

- The balanced accuracy score is 53%.
- The high_risk precision is about 1% with a 61% recall score.
- The low_risk population has a precision of 100% with a recall score of 45%

SMOTEENN Accuracy Score:

![SMOTEENNacc](https://github.com/coxjack/Credit_Risk_Analysis/blob/main/Additional%20Images/SMOTEENN_accscore.png)

SMOTEENN Confusion Matrix:

![SMOTEENNcm](https://github.com/coxjack/Credit_Risk_Analysis/blob/main/Additional%20Images/SMOTEENN_cm.png)

SMOTEENN Classification Report:

![SMOTEENNcr](https://github.com/coxjack/Credit_Risk_Analysis/blob/main/Additional%20Images/SMOTEENN_classreport.png)

- The balanced accuracy score is 64%.
- The high_risk precision is about 1% with a 71% recall score.
- The low_risk population has a precision of 100% with a recall score of 56%

BalancedRandomForestClassifier Accuracy Score:

![BalancedRandomForestClassifieracc](https://github.com/coxjack/Credit_Risk_Analysis/blob/main/Additional%20Images/BRFC_accscore.png)

BalancedRandomForestClassifier Confusion Matrix:

![BalancedRandomForestClassifiercm](https://github.com/coxjack/Credit_Risk_Analysis/blob/main/Additional%20Images/BRFC_cm.png)

BalancedRandomForestClassifier Classification Report:

![BalancedRandomForestClassifiercr](https://github.com/coxjack/Credit_Risk_Analysis/blob/main/Additional%20Images/BRFC_classreport.png)

- The balanced accuracy score is 79%.
- The high_risk precision is about 3% with a 70% recall score.
- The low_risk population has a precision of 100% with a recall score of 87%

EasyEnsembleClassifier Accuracy Score:

![EasyEnsembleClassifieracc](https://github.com/coxjack/Credit_Risk_Analysis/blob/main/Additional%20Images/EEC_accscore.png)

EasyEnsembleClassifier Confusion Matrix:

![EasyEnsembleClassifiercm](https://github.com/coxjack/Credit_Risk_Analysis/blob/main/Additional%20Images/EEC_cm.png)

EasyEnsembleClassifier Classification Report:

![EasyEnsembleClassifiercr](https://github.com/coxjack/Credit_Risk_Analysis/blob/main/Additional%20Images/EEC_classreport.png)

- The balanced accuracy score is 93%.
- The high_risk precision is about 9% with a 92% recall score.
- The low_risk population has a precision of 100% with a recall score of 94%

## Summary
-When compared to the other models the EasyEnsembleClassifier is the most effective. It provides the highest score across all loans no matter the risk.
- All of the models demonstrate a low precision score
- In general, the EasyEnsembleClassifier will perform the best and give the lending services company the best chance to analysis credit risk.
