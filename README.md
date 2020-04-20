# Telecom Churn Prediction
In the Telecom Industry, Customers are able to choose from multiple service providers and actively switch from one Operator to another. Due to the technical progress and the increasing Number of Operators raised the level of competition. Hence, for the Telecom Companies Predicting the Customers who have High Risk of getting into Churn Proactively has become important.

Telecom Companies follow three main strategies to Generate More Revenues:

 - Acquire New Customers
 - Upsell the Existing Customers
 - Increase the Retention Period of Customers
However, comparing the above Strategies Taking the Value of Return on Investment (RoI) of each into account has shown that the Increase the Retention Period of Customers, is the most Profitable Strategy. In this highly competitive market, the Telecom Industry experiences an average of 15-25% annual Churn rate. Given the fact that it costs 5-10 times more to acquire a new customer than to retain an existing one. So, for most of the Telecom Operators the Customer Retention has now become even more important than Customer Acquisition.

### Customer Churn Rate:

Churn Rate is the percentage of subscribers to a service, who had discontinued their Service in a given time period.

#### Importance:

Churn Rate indicate the Strength of a Company’s Customer Service and its overall Growth.
Lower the Churn Rate of a Company, the better it is in its Competitive State.
It is always more Difficult and Expensive for a Company to Acquire a New Customer than it is to retain a Current Paying Customer.
If we Predict Customers who are at High Risk of Churning, there will be still time to Take Necessary Actions for the Company about their Customers to reduce the Churn Rate.

So, the Task here is to Predict the Customers at High Risk of Churn Using Machine Learning.

#### Objectives and Constraints:
To Predict as many customers as possible with the best possible Score.
No Low Latency Constraint.

#### Performance Metrics:
 - AUC Score
 - F1 Score

#### F1 Score:
As the Dataset is Highly Imbalanced, the positive class makes just over 7.32% of the total. So, a metric such as F1 Score seems appropriate for this kind of problem as it considers both precision and recall of the test to compute the score.   

#### Reason for Choosing AUC:
As, The Dataset is Imbalanced and it is Binary Classification, AUC has better Sensitivity to the Imbalanced Dataset. Whereas, the Accuracy Fails in this Case.

### Data:

The Data set can be downloaded from https://www.kaggle.com/vijaysrikanth/telecom-churn-data-set-for-the-south-asian-market
The Data set is Based on South Asian Users.

 - File format: .csv
 - Size: 75.4 MB
 - Number of Data Points: 99999
 - Number of Columns: 226
