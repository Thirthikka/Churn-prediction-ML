# Churn-prediction-ML
This study develops a **machine learning approach** for **predicting customer churn in the banking sector**. 
The objective is to classify customers as Existing or Attrited based on demographic, account and transaction characteristics. The prediction can help banks identify customers at risk of leaving and take proactive retention measures. Since missing an actual churner can be costly, recall is an important evaluation metric.
The methodology involves data preparation, preprocessing, model development and evaluation. The unique **CLIENTNUM identifier** is removed, and **Attrition_Flag** is converted into a **binary target**. Categorical variables are transformed using hierarchical mapping, dummy encoding and label encoding. The data is then divided into 70% training and 30% testing sets using stratified sampling.
Three classifiers— **Decision Tree, Random Forest and Gradient Boosting**—are evaluated using **accuracy, precision, recall and F1-score**. The Decision Tree achieves approximately **93% test accuracy**, but its perfect training performance indicates **overfitting**. 
The ensemble models perform better, with Random Forest and Gradient Boosting achieving approximately **96% test accuracy**. 
Gradient Boosting provides the best overall balance, with approximately **93% precision, 81% recall and 86% F1-score**.
Feature-importance analysis shows that transaction-related variables are highly influential. **Total_Trans_Ct** is the most important feature with an importance of 0.33, followed by transaction amount, revolving balance and relationship count.
Overall, the results demonstrate that customer behaviour and account activity can effectively support churn prediction and customer retention planning.
