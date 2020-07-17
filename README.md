# **Understanding Customer Churn – Prediction and prevention**
Customer churn, also known as customer attrition, refers to when a customer cancels his or her subscription or ceases his or her relationship with a company. 
Every company defines churn differently. For instance, an online retail company may consider a customer churned when the customer hasn’t bought something in say three months. A telecom company may define it when a customer explicitly cancels their subscription or doesn’t renew one. However may the companies choose to define it, it remains a critical metric for revenue generation, growth and profits. After all, each lost customer is loss in revenue lost and increase in marketing costs. According to Forbes, it can cost five times more to attract a new customer, than it does to retain an existing one. 
Moreover, research shows that loyal customers tend to spend more than new customers. Thus, it will always do well to retain customers and avoid churn. In fact, a happy, satisfied and loyal customer can help with word-of-mouth marketing and steer new customers.

 
![](Images/Statistics.png)

[Image Source](https://www.ocreativedesign.com/customer-retention-using-marketing-automation/)

As I’m quite interested in ecommerce, I wanted to work with a churn dataset to develop a machine learning algorithm to predict churn.

## **Project workflow**
For the project I tried to follow a typical data science project workflow. 
![](Images/ProjectWorkFlow.png)
 

## **The dataset**
After identifying the business problem of customer churn that I wanted to help solve, I looked for a dataset. I have used a publicly available dataset from [Kaggle](https://www.kaggle.com/blastchar/telco-customer-churn).

This is a relatively clean however imbalanced dataset, and provides ample opportunity to explore the data, make some meaningful visualizations, derive insights and build machine learning algorithms to make predictions.

Here's a brief data dictionary:
* Customers who left within the last month – this column is called Churn
* Services that each customer has signed up for – phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies
* Customer account information – how long they’ve been a customer, contract, payment method, paperless billing, monthly charges, and total charges
* Demographic information about customers – gender, age range, and if they have partners and dependents

## **Exploratory analysis**
* Customers with basic services are more likely to churn, thus it might do good to offer some services like tech support or online protection either free or may be at a promotional rate. This might help to improve the customer experience and loyalty, and thus reduce chances of churn.
* Also, customers with no dependents or partners have more chances of leaving, thus, promotional deals for this segment who have opted for basic facilities could be focussed upon.
* Also, the shorter the contract, the more the chances of churn. Thus, deals with longer contract should be made more enticing for the customers.
* Further, customers with fibre-optic internet services, paperless billing options and electronic check payment method are more possible to leave.




