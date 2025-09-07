# Loan_Default_Predictor
Loan Default Prediction using Machine Learning | Applied SMOTE for class imbalance, implemented Random Forest, XGBoost &amp; Ensemble methods, and optimized performance using Recall, F1-score, and ROC-AUC
<br>
Author : Reenu LK
<br>
<b>DATASET</b>
<p>Souce : Kaggle</p><br><p>Size : (255347, 18)</p>
<p>Target : 0(Not default) 1 (default)</p>
<p>Features : Age, Income, Loan Amount, Credit Score, Employment, etc.</p>
<b>APPROACH</b><br> <p>Data preprocessing like detecting null values,duplicate values , removing outliers if found,encoding and Standard scaling</p>
<p>Handling class imbalance using SMOTEEN</p>
<p>ML algorithms used :Logistic Regression,Random forest classifier,xgboost,balanced random classifier and Easy ensemble</p><br>
<b>RESULTS</b>
<p>Evaluation metrics used : Recall, Precision,Accuracy,ROC-AUC </p>
<p>Random forest classifier has highest accuracy but poor recall(for default case)which is essential for such problem</p>
<p>Logistic regression and Easy ensemble have best recall(for default case) </p>
