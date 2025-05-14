**Diwali Sales Data Analysis**


This project analyzes the sales data for Diwali. The dataset includes customer demographics, purchase behavior, and sales information across various product categories. The analysis provides insights into factors such as gender, age group, marital status, occupation, and product categories that influence customer behavior.

Steps and Analysis:
Data Import & Exploration:

The data was imported from a CSV file (Diwali Sales Data.csv) using Pandas.

Data consists of 11,251 entries with 15 columns, including customer information, purchase details, and more.

Data Cleaning:

Removed irrelevant columns (Status and unnamed1), which contained no useful data.

Addressed missing values by dropping rows with null values.

Changed the data type of the Amount column to int for consistency.

Renaming Columns:

Renamed the Marital_Status column to Shaadi for better clarity.

Descriptive Statistics:

Used the describe() method to gain insights into numerical columns like Age, Orders, and Amount.

Notable insights: The average customer age is ~35 years, with an average order count of around 2.5 and an average purchase amount of ₹9,453.

Exploratory Data Analysis (EDA):

Gender Analysis:

Visualized gender distribution, revealing that most buyers are females with higher purchasing power.

Aggregated sales by gender showed that females contributed more to the total sales.

Age Group Analysis:

Visualized the most frequent age groups and their purchasing power, with the highest sales coming from the 26-35 age group.

State Analysis:

Analyzed sales from different states, identifying Uttar Pradesh, Maharashtra, and Karnataka as the top states contributing to the most orders and sales.

Marital Status Analysis:

Most of the buyers are married, especially females, who tend to make higher purchases.

Occupation Analysis:

Identified IT, Healthcare, and Aviation as the sectors with the highest sales, with most buyers being employed in these fields.

Product Category Analysis:

The top-selling product categories were Food, Clothing, and Electronics.

The most sold products were also identified based on total orders.

Visualizations:

Created multiple visualizations using Seaborn and Matplotlib to represent the distribution of customers, total sales, and top products by various factors (gender, age group, marital status, occupation, product category).

Key Insights:

Marital Status: Married women in the 26-35 age group have the highest purchasing power.

Location: Uttar Pradesh, Maharashtra, and Karnataka contribute significantly to overall sales.

Occupation: Customers from IT, Healthcare, and Aviation sectors tend to make the most purchases.

Product Preferences: Customers primarily purchase from the Food, Clothing, and Electronics categories.

Conclusion:
The analysis highlights that married women aged 26-35, particularly from Uttar Pradesh, Maharashtra, and Karnataka, working in IT, Healthcare, and Aviation sectors, are the most active buyers. The most purchased products are from the Food, Clothing, and Electronics categories.
