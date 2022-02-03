# Credit_Risk_Analysis

Overview of the loan prediction risk analysis
The objective of this challenge is to use different machine learning algorithms to predict credit card risk . Use differnt techniques like data preprocessing , data transformation, boosting, bagging, oversampling , undersampling etc to find good candidate for loan.

Resources
*LoanStats_2019Q1.csv

Technologies Used
Jupyter Notebook
Results
The following section shows comparasion for prediction results of oversampling , undersampling and ensembling .

if we talk about accuracy score than out of four oversampling and undersampling algorithms randomoversampling,SMOTE and SMOTEENN have around 65 % accurate.But compare to sampling algorithms ensembling algorithms give more accuracy here balanced random forest classifier give 79 % accuracy and EasyEnsembleClassifier is 93% accurate.
same with recall(sensitivity) that RandomOversampling ,SMOTE and SMOTEENN provide almost same recallAlso ensampling techniques have a good sensitivity value here BalencedRandomforest give 70% recall for low risk and 88% for high risk. EasyEnsembleClassifier give 92% recall for low risk and 94% for high risk.
After comparing accuracy score ,precision and recall we can conculde that EasyEnsembleClassifier algorithm give good prediction among six algorithms.
RandomOversampling
SMOTE
Undersampling
SMOTEENN
BalancedRandomforest
EasyEnsembleClassifier


Summary

From above analysis we can say that comapare to oversampling and undersampling ensamble algorithms give good prediction results. Both ensamble algorithm give good prediction but BalancedRandomforest algorithmm is best fir for our analysis because its provide 93.28 %accuracy as well as good recall and F1-score for High-risk.
