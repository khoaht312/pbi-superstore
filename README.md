This project is a report on sales and profit for the fictional company "Superstore" based on their sales and profit data. The report also includes customer segmentation using RFM Analysis and K-means clustering. The data used in this project is a sample dataset provided by Superstore.

## Technologies Used
- Python (Pandas, NumPy, Scikit-learn)
- Power BI
## Data Source
The data source used in this project is the Superstore sample dataset provided by Superstore. The dataset contains information on sales and profit, including customer information.
Dataset: https://www.kaggle.com/datasets/juhi1994/superstore

## Project Description
This project is divided into two main parts: Visualization and Analysis.

## Visualization
The visualization part of this project is created using Power BI. The visualizations are created to show the sales and profit trend over time, sales and profit by category and sub-category, and sales and profit by region. The visualizations also include interactive filters, such as the ability to filter by year, customer, and region.

## Analysis

**Insights**:
- The Central region has the highest total sales and profit, while the South region has the lowest.
- Furniture has the lowest profit margin of all the product categories, while Technology has the highest.
- Orders placed via the phone have a higher average order value than those placed online or via mail.
- Customers in the Home Office segment have the highest average order value, while those in the Consumer segment have the lowest.
- Sales and profit both tend to be higher in the second half of the year (July to December) than in the first half (January to June).
- There is a positive correlation between sales and profit, but the strength of the correlation varies by region.
- The top-performing products by sales and profit are concentrated in the Technology and Office Supplies categories.
- There are some customers who consistently generate high sales and profit, while others only make occasional purchases with lower values.
- There are some sub-categories (such as Machines and Tables) with consistently low profit margins, indicating that the company may need to re-evaluate pricing or sourcing strategies for those products.

The analysis part of this project involves customer segmentation using RFM Analysis and K-means clustering. RFM Analysis is a technique used to segment customers based on their recency, frequency, and monetary value. K-means clustering is a machine learning algorithm used to group similar data points together.

The RFM Analysis involves calculating the recency, frequency, and monetary value of each customer. The recency is calculated as the number of days since the customer's last purchase. The frequency is calculated as the number of purchases made by the customer. The monetary value is calculated as the total amount spent by the customer. The customers are then segmented into three groups based on their RFM scores.

K-means clustering is used to group customers based on their RFM scores. The optimal number of clusters is determined using the elbow method. The customers are then assigned to one of the clusters based on their RFM scores.

## How to Use
- Download the Superstore sample dataset.
- Run the Python script "Customer-Segmentation.ipynb" to perform the RFM Analysis and K-means clustering and save the results as a CSV file.
- Open the Power BI file "SPD.pbix" to view the visualizations.

## Conclusion
This project provides a comprehensive report on sales and profit for Superstore, along with customer segmentation using RFM Analysis and K-means clustering. The visualizations in the report allow the user to easily identify trends and patterns in the data, while the customer segmentation allows Superstore to target specific customer groups with personalized marketing strategies.

![PBI-1](https://github.com/tedhwang007/pbi/blob/main/IMG/report.png)



