# Credit_Risk_Analysis
Challenge 17 for Butler Data Science

## Analysis 
Several machine learning models were used to analyze and  predict credit risk.\

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
- The low_risk population, has a precision of almost 100% with a recall score of 68%
