# Customer Shopping Behavior Analysis Project Overview:
A leading retail company wants to better understand its customers’ shopping behavior in order to improve sales, customer satisfaction, and long-term loyalty. They are particularly interested in uncovering which factors, such as discounts, reviews, seasons, or payment preferences, drive consumer decisions and repeat purchases.
You are tasked with analyzing the company’s consumer behavior dataset to answer the following overarching business question: “How can the company leverage consumer shopping data to identify trends, improve customer engagement, and optimize marketing and product strategies?”

## Objectives:
- Data Preparation & Modeling (Python): Clean and transform the raw dataset for analysis.
- Data Analysis (SQL): Organize the data into a structured format, simulate business transactions, and run queries to extract insights on customer segments, loyalty, and 
  purchase drivers.
- Visualization & Insights (Power BI): Build an interactive dashboard that highlights key patterns and trends, enabling stakeholders to make data-driven decisions.
- Report: Write a clear project report summarizing your key findings and business recommendations.

## Dataset Summary:
- Rows: 3,900
- Columns: 18
- Key Features:
- Customer demographics (Age, Gender, Location, Subscription Status) - Purchase details (Item Purchased, Category, Purchase Amount, Season, Size, Color) - Shopping behavior (Discount        Applied, Promo Code Used, Previous Purchases, Frequency of Purchases, Review Rating, Shipping Type)
- Missing Data: 37 values in Review Rating column 
        
## EDA:
- Handled Missing values
- Column standardization

## Feature Engineering:
- Created age_group column by binning customer ages.
- Created purchase_frequency_days column from purchase data.

## Data Validation:
- Data Consistency Check: Verified if discount_applied and promo_code_used were redundant; dropped promo_code_used.

## Database Integration:
- Connected Python script to PostgreSQL and loaded the cleaned DataFrame into the database for SQL analysis.

## Data Analysis using SQL
- We performed structured analysis in PostgreSQL to answer key business questions mentioned in the report.

## Dashboard in Powerbi:
![Coffee Sales Dashboard](https://github.com/skhare075/Customer_Trend-_Analysis_using_Python_SQL_Powerbi/blob/main/Customer%20Sjopping%20Behaviour%20powerbi.png)
