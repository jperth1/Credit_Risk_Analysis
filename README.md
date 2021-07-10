# Credit_Risk_Analysis

The purpose of this analysis is produce six different supervised machine learning learning models to evaluate which model is best when it comes to predicting credit card risk. 

### Random oversampling

-	Balanced accuracy score is .640, the model correctly predicted cases as high-risk and low-risk 64% of the time 
-	the average precision is .99, or 99%, however the model predicted a high number of false positives where 6,546 cases were predicted as high risk but were actually low risk
-	The average recall, or sensitivity  is 62%, with the model correctly predicting high risk  66% and low risk at 62% of the time

![Random_Oversampling_Accuracy_Score](/Resources/Random_Oversampling_Accuracy_Score.png)

![Random_Oversampling_Report](/Resources/Random_Oversampling_Report.png)


### SMOTE Oversampling

-	Balanced accuracy score is .651, the model correctly predicted cases as high-risk and low risk 65.1% of the time
-	The average precision is .99, or 99%, however the model predicted a high number of false positives where 7,566 cases were predicted as high risk but were actually low risk
-	The average recall or sensitivity is 69%, with the model correctly predicting high risk 61% of the time and low risk 69% of the time

![SMOTE_Oversampling_Accuracy_Score](/Resources/SMOTE_Oversampling_Accuracy_Score.png)

![SMOTE_Oversampling_Report](/Resources/SMOTE_Oversampling_Report.png)


### Under sampling

-	Balanced accuracy score is .651, the model correctly predicted cases as high-risk and low-risk 65.1% of the time.
-	The average precision is .99 or 99%, however the model predicted a high number of false positive where 5,317 cases were predicted as high risk but were actually low risk
-	The average recall is 69% with the model correctly predicting high risk 61% of the time and low risk 69% of the time

![Undersampling_Accuracy_Score.png](/Resources/Undersampling_Accuracy_Score.png)

![Undersampling_report.png](/Resources/Undersampling_report.png)


### Combination (Over and Under) Sampling

-	Balanced accuracy score is .544, the model correctly predicted cases as high risk and low risk 54.4% of the time
-	The average precision is .99% however the model predicted a high number of false positives where 5,317 cases were predicted as high risk but were actually low risk
-	The average recall is 56% with the model correctly predicting high risk cases 75% of the time and low risk cases 56% of the time

![Combination_Accuracy_Score](/Resources/Combination_Accuracy_Score.png)

![Combination_Report](/Resources/Combination_Report.png)


### Balanced Random Forest Classification

-	Balanced accuracy score is .683, the model correctly predicted cases as high-risk and low-risk 68.3% of the time
-	The average precision is 100%, with 5 false positives and 64 false negatives predicted
-	The average recall is 100%, with 100% recall for low-risk cases, but 37% recall with high-risk cases

![Random_Forest_Accuracy_Score](/Resources/Random_Forest_Accuracy_Score.png)

![Random_Forest_Report](/Resources/Random_Forest_Report.png)

### Easy Ensemble Classification
-	Balanced accuracy score is .935, the model correctly predicted cases as high-risk and low-risk 93.5% of the time
-	The average precision is 99% with 985 cases of false positives and 8 cases of false negatives
-	The average recall is 94% with 92% of cases correctly predicted as high-risk and 94% of cases correctly predicted as low-risk.

![EEC_Accuracy_Score](/Resources/EEC_Accuracy_Score.png)

![EEC_Report](/Resources/EEC_Report.png)


## Summary

It is recommended to use the Easy Ensemble Classification supervised learning model because it in the testing and training it has shown the most success in correctly predicting both high-risk and low-risk loan cases. Out of all the supervised learning models the easy ensemble classification has the highest recall for both high-risk and low-risk cases, 94% and 92% respectively. 

