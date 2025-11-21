# ZEE’S SHOP CUSTOMER PURCHASING HABITS AND BEHAVIOUR
Analysis of Customer Purchase Behaviour from Zee's Mart  Customer Dataset.


![](Dash1.jpg)
 
## Introduction

This project analyzes transactional data from *ZEE’s online retail shop* to uncover customer purchase habits and behaviors. By understanding patterns such as purchase frequency, average order value and product preferences, we aim to uncover actionable insights that could optimize sales strategies, improve marketing campaigns and enhance customer retention efforts.

Goal of Analysis
1.	To analyze overall customer dataset and identify high-performing products and customer segments.
2.	To derive data backed insights that could help stakeholders to improve customer experience, sales strategies, Project strategies and marketing efforts.
 
 
## Problem Statement
The stakeholders of ZEE’s shop wanted to move away from "mass marketing" and towards "targeted marketing."  They want to better understand its customers’ shopping behavior in order to improve sales, customer satisfaction, and long-term loyalty. The management team has noticed changes in purchasing patterns across demographics, product categories, and sales channels (online vs. offline). They are particularly interested in uncovering which factors, such as discounts, reviews, seasons, or payment preferences, drive consumer decisions and repeat purchases. 

The Challenge: The marketing team struggled to distinguish between high-value loyalists and one-time shoppers. They needed a data-driven approach to segment their audience and optimize ad spend. “How can the company leverage consumer shopping data to identify trends, improve customer engagement, and optimize marketing and product strategies?”

 

📂 Dataset Description
The dataset used in this analysis contains transactional data from an online retail store. It includes customer information, product details, and purchase history. 
Rows: 3,900, Columns: 18 

Key Features:
o	Customer demographics (Age, Gender, Location, Subscription Status) 
o	Purchase details (Item Purchased, Category, Purchase Amount, Season, Size, Color) 
o	Shopping behavior (Discount Applied, Promo Code Used, Previous Purchases, Frequency of Purchases, Review Rating, Shipping Type) 
o	Missing Data: 37 values in Review Rating column
##  ⚙️ Tools/ Skill and Methodologies demonstrated 
The following tools and technologies were used to perform this analysis:
1.	Excel: - To preview and do basic cleaning
2.	Python: Data Preparation and Advance cleaning.
Pandas: For data manipulation and cleaning. 
-	Exploratory Data Analysis (EDA)
-	Missing Data Handling
-	Column Standardization
Data Consistency Check
-	 Database Integration
NumPy: For numerical operations.
Jupyter Notebooks: Used for interactive analysis and visualizations.

3.	SQL:  PostgreSQL 
-	For querying data stored in relational databases.
-	performed structured analysis in PostgreSQL to answer key business questions


4.	POWER BI
-	Build interactive dashboard in Power BI to present insights visually
-	Made use of measure, slicer, Filters, 
 

## Modelling
Automatically derived relationships are adjusted to remove and replace unwanted relationships with the required.
There are 5-dimention table s and 1 fact table. The dimension tables are all joined to the fact table with one-to-many relationship.
 
Adjusted Model          |     Auto Model
:----------------------:|:-------------------------:
![](Dash1.jpg )        | ![](Dash2.jpg)
 
 
## Visualization:
 
The report comprises of 4 pages:
1. Customer hx
2. Product catalog
3. Transaction hx
4. Warehouse
 
You can interact with report [here](powerBI service link here)
 
![](Dash1.jpg)
Feature:
- The four tabls are buttons with hovering effect and each navigates to the page with similar name.
- Hamuger is button to display the country and month filters while the red coloured "X'  button close the filter.
 
## Analysis
 
🔑 Key Findings
Here are some key insights drawn from the analysis:
1.	Purchase Frequency: Customers with high purchase frequency tend to have higher lifetime value, which suggests they may be more loyal to the brand.
2.	Product Preferences: Electronics and clothing items showed the highest sales, with electronics being particularly popular during holiday seasons.
3.	Customer Segmentation: Customers who purchased at least once a month were categorized as frequent buyers, contributing to 70% of total sales.
4.	Seasonal Trends: Sales peaked around Black Friday and other major shopping holidays, while the summer months saw a dip in purchases.
5.	Demographic Insights: Younger customers (18-35) had higher spending in electronics, while middle-aged customers (36-50) preferred clothing and home goods.


### Customer History: 
 
![](dash2.jpg)
 
The store currently have a total of 1765 customers.
330k orders were made in the current year.
 
### Product catalog
 
![](dash1.jpg)
 
there are 128 products in the stores with worth of 140 million dollars.
Each product cost more than 1K dollars on average.
 
### Transaction History:
 
![](dash1.jpg_)
 
Total selling pricee is 140 million.
The highest gross income was generated in July.
There is an intermittent rise and fall in the gross income of the store by every month in the current year.📉
 
## Conlusion and Recommendation
 
- Illinois has the highest impact on the income althogh relatively negligible. 💵
- There are 128products in the stores with a worth of 140 million dollars. 😄 🤓
 
# Recommendation:
For a deep dive into the analysticsm, the datasets of the previous years will be required for comparison and data driven decision making. 🙏


