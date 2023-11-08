# Telecom-Churn-Analysis-with-IBM-Business-Analytics

In this project, we will analyze Telco customer churn data, which contains information about a fictional telecom company that provided home phone and Internet services to 7,043 customers in California during Q3. Each row represents a customer, and each column contains customer attributes described in the column metadata.

The analysis will be performed using Python.

The dataset can be found on Kaggle at the following link: [Telco Customer Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn#WA_Fn-UseC_-Telco-Customer-Churn.csv).

We will address the following questions in this analysis:

1. What is the average monthly cost based on their payment method?
2. How is customer tenure distributed into three groups:
   - Low: Customers with tenure < 21 months
   - Medium: Customers with tenure between 21 and 40 months
   - High: Customers with tenure > 40 months
3. Are there a significant number of senior citizens using telephone services?
4. What is the distribution of the total cost?
5. Do customers with higher monthly costs tend to churn more frequently?
6. How does the presence of a partner and dependents impact customer churn rates?
7. Which payment method exhibits the highest churn rate among customers?

# Analysis
## 1. Segmentation by Payment Method
<img width="1162" alt="image" src="https://github.com/rizcazahra/Telecom-Churn-Analysis-with-IBM-Business-Analytics/assets/84758353/b6830b41-677a-4f59-a029-f89aff12ac57">
From the plot above, it can be concluded that:
* The payment method with the highest monthly charge per customer is Electronic Check, amounting to $76.26.
* The lowest monthly charge per customer is using mailed check, with a monthly charge of $43.92.

## 2. Customer Tenure Segmentation
<img width="1041" alt="image" src="https://github.com/rizcazahra/Telecom-Churn-Analysis-with-IBM-Business-Analytics/assets/84758353/2b409177-546d-4e21-a3df-a3c97d3d9388">
It can be concluded that the highest number of customers is in the low tenure group, with a total of 2,878 customers, and the lowest number of customers is in the medium tenure group, with 1,408 customers.

## 3. Senior Citizen Analysis
<img width="1070" alt="image" src="https://github.com/rizcazahra/Telecom-Churn-Analysis-with-IBM-Business-Analytics/assets/84758353/bf84dfdb-ceaa-4c23-8919-861ca355eaf3">

It can be concluded that around 90% of both senior and non-senior citizens use telephone services.

## 4. Total Cost Distribution
<img width="1199" alt="image" src="https://github.com/rizcazahra/Telecom-Churn-Analysis-with-IBM-Business-Analytics/assets/84758353/f5010a0b-4225-4d76-8f31-746f49c48ca0">
The majority of the total customer charges are below 2000.

## 5. Monthly Cost and Churn Analysis
<img width="944" alt="image" src="https://github.com/rizcazahra/Telecom-Churn-Analysis-with-IBM-Business-Analytics/assets/84758353/ed413d4a-1ffa-49b7-8c04-cb0d470e43ba">

The customers with high monthly charges (between 70 and 118) are more likely to churn compared to those who have lower monthly charges.


## 6. Partner and Dependents Impact on Churn
<img width="851" alt="image" src="https://github.com/rizcazahra/Telecom-Churn-Analysis-with-IBM-Business-Analytics/assets/84758353/d5485f13-2d15-4335-909e-7e194a113083">
"The Churn Rate is Lowest for Customers with Both Partners and Dependents (Yes-Yes)

## 7. Payment Method and Churn Analysis
<img width="928" alt="image" src="https://github.com/rizcazahra/Telecom-Churn-Analysis-with-IBM-Business-Analytics/assets/84758353/534c8e16-7678-4891-864c-3030af5acff6">
In the graph above, it can be concluded that customers who make payments using Electronic Check have the highest churn rate (orange) compared to other payment methods. Conversely, customers who opt for Bank Transfer, Credit Card, and Mailed Check as their payment methods have a significant tendency not to churn.
