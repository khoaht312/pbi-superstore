## Case Study: Business Problem
A large retailer, Superstore, wants to improve its marketing strategy to boost sales and profits. To achieve this goal, they need to understand their customers better and segment them into different groups based on their buying behavior. The retailer has collected transactional data, which includes the date, product category, customer ID, sales, and profit margin. They want to use this data to segment their customers and identify the most profitable customer groups.

## Data Exploration
We will be using the Superstore dataset, which contains transactional data for a period of 4 years from 2014 to 2017. The dataset contains 51,290 rows and 24 columns, including Order ID, Order Date, Ship Date, Ship Mode, Customer ID, Segment, Country, City, State, Region, Product ID, Category, Sub-Category, Product Name, Sales, Quantity, Discount, and Profit.

## Data Preparation
First, we will preprocess the data by cleaning the missing and duplicate values. Next, we will perform feature engineering to extract the RFM (Recency, Frequency, and Monetary) values for each customer.

Recency represents the number of days since the last purchase by a customer, Frequency represents the number of purchases made by a customer, and Monetary represents the total amount of money spent by a customer.

We will also normalize the data using the MinMaxScaler to bring all the features to a common scale.

## RFM Analysis
After preparing the data, we will perform RFM analysis to segment the customers based on their buying behavior. We will use the K-means clustering algorithm to group customers into different segments.

We will determine the optimal number of clusters using the Elbow method and Silhouette analysis.

## Results and Insights
After performing the clustering, we will analyze the results and draw insights. We will identify the most profitable customer groups and make recommendations to improve the marketing strategy to target these customers.

For example, we may find that customers who purchase office supplies in large quantities are the most profitable group. In this case, we may recommend launching targeted marketing campaigns for this group to increase their loyalty and purchase frequency.

## Conclusion
Customer segmentation is an important aspect of marketing strategy, and RFM analysis combined with K-means clustering is an effective way to segment customers based on their buying behavior. The Superstore dataset provides a rich source of transactional data that can be used to identify the most profitable customer groups and make data-driven marketing decisions.

Dataset: https://www.kaggle.com/datasets/juhi1994/superstore

![PBI](https://github.com/tedhwang007/pbi/blob/main/Screenshot.png)

