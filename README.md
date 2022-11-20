# Churn-analysis-and-prediction

This project analyses the customer data of a leading telecom company in Asia region. The dataset contains data for four months from which the goal is to identify
customers who will churn in the last month. in telecom industry it is a costly affair to bring in new customers than preserving existing base. So by identifying which 
customers might churn in advance it is possible to curb it. To derive maximum benefit we target high value customers who generate 80% f the revenue.
To build the model the following steps were followed:

1.Preprocess data - Converting columns to appropriate format, handle missing values

2.Perform EDA - Exploratory data analysis to detect outliers , correlations etc.

3.Deriving new features.

4.Apply PCA to reduce number of predictors

5.Handling class imbalance using SMOTE

6.Train the models and tune the hyperparameters.

7.Evaluate models based on metrics. Since the goal is to identify churn accurately we use AUC to measure performance. We evaluate Logistic regression with PCA and random forests models.

8.PCA with Logistic regression performs better in this scenario, hence we use this model to identify churn with 90% accuracy

9.We use random forests to derive the top 10 features influencing churn and make suggestions based on this information.

