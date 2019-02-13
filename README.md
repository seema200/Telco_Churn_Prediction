# Telco_Churn_Prediction

Churn is a one of the biggest problem in the telecom industry. Research has shown that the average monthly churn rate among the top 4 wireless carriers in the US is 1.9% - 2%. In this analysis I have first developed some hypothesis by conducting a detailed exploratory data analysis for churn in the telecom industry and used predictive analytics to accurately identify the customers who are likely to churn.
<br> <br>
I have explored the following classficiation techniques and compared their accuracy and other metrics such as ROC-AUC score.
<br> <br>
<b>Models Explored</b>
<br>
Logistic Regression<br>
Decision Tree<br>
Random Forest<br>
ADABoost
<br> <br>
<b>Overall approach is as follows:</b>
<br>
Data Preprocessing - To check for any missing values, correlated variables and dummy encoding<br>
EDA to develop hypothesis<br>
Scaling data to make sure we are using scaled data to improve accuracy<br>
Splitting data into train & test datasets<br>
Training each of the above models<br>
Testing the accuracy on test data and plotting ROC curves for each of the models<br>
