# Loan_Default_Predictor
Loan Default Prediction using Machine Learning | Applied SMOTE for class imbalance, implemented Random Forest, XGBoost &amp; Ensemble methods, and optimized performance using Recall, F1-score, and ROC-AUC
<br>
Author : Reenu LK
<br>
<b>DATASET</b>
<br>
<p>Souce : Kaggle</p><br><p>Size : (255347, 18)</p>
<br><p>Target : 0(Not default) 1 (default)</p><br>
<p>Features : Age, Income, Loan Amount, Credit Score, Employment, etc.</p><br>
<b>APPROACH</b><br> <p>Data preprocessing like detecting null values,duplicate values , removing outliers if found,encoding and Standard scaling</p><br>
<p>Handling class imbalance using SMOTEEN</p><br>
<p>ML algorithms used :Logistic Regression,Random forest classifier,xgboost,balanced random classifier and Easy ensemble</p><br>
<b>RESULTS</b><br>
<p>Evaluation metrics used : Recall, Precision,Accuracy,ROC-AUC </p><br>
<p>Random forest classifier has highest accuracy but poor recall(for default case)which is essential for such problem</p><br>
<p>Logistic regression and Easy ensemble have best recall(for default case) </p>
