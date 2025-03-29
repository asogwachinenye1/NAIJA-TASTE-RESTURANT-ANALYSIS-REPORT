# NAIJA-TASTE-RESTURANT-ANALYSIS-REPORT
This project analyzes sales data from Naija Tastes Restaurant, a fast-growing eatery in Lagos, Nigeria. Using python-based data analysis, the goal was to uncover insights into sales performance, customer behavior, and business trends. The findings support revenue optimization, improved customer engagement, and data-driven decision-making.

Navigation Menu
Sign in
DataProfessor290
/
Naija-Tastes-Resturant-Sales-Analysis
Public
This project analyzes sales data from Naija Tastes Restaurant using SQL to uncover business insights. It includes data cleaning, revenue analysis, customer behavior insights, and sales trends to optimize decision-making and improve customer experience.


Resturant Analysis on python

customers.csv

products.csv

sales.csv


# Introduction
Naija Tastes Restaurant, a fast-growing eatery in Lagos, Nigeria, is dedicated to offering delicious local delicacies. This report provides data-driven insights into sales performance, customer behavior, and business trends using SQL-based data analysis. The insights aim to enhance revenue generation, improve customer experience, and optimize business operations.

# Data Cleaning & Wrangling
To ensure accurate and meaningful insights, the dataset was cleaned and transformed through the following steps:
* Data Type Standardization:Converted sale_date column to DATE format.
* Converted product_id and customer_id to TEXT for proper referencing.
* Handling Missing Values:Identified and removed rows where critical fields (quantity, total_price, payment_method, sale_date, product_name, price) contained NULL values.
* Merging Datasets:Joined customer_sales and products tables to create a merged_table with relevant fields.
* Feature Engineering:Extracted sales_month, month_no, day_of_week, and day_number from sale_date for deeper analysis.
* Duplicate Checks:Verified uniqueness of data entries to ensure no duplicate transactions were present.
These steps ensured a clean dataset for analysis, improving the reliability of insights.

# Sales Performance Analysis
## Top-Selling Products
Suya & Chips recorded the highest sales at ₦343,000, indicating strong customer preference.
Traditional Nigerian meals were dominant among bestsellers, including:
Amala & Ewedu (₦318,600)
Eba & Ogbono Soup (₦310,800)
Jollof Rice & Chicken (₦237,500)
Palm Wine (₦226,800), showing demand for traditional beverages.
## Bottom-Selling Products
Zobo Drink had the lowest sales at ₦110,000, indicating lower customer demand.
Other low-performing products include:
Chapman (₦153,000) and Pepper Soup (₦162,000) had moderate sales.
Pounded Yam & Egusi (₦201,000) and Fried Rice & Beef (₦223,100) performed slightly better but remained among the lower-selling items.

 # Revenue Analysis
* Revenue in the Last 3 Months
December: ₦740,000
January: ₦761,800 (peak sales month)
February: ₦191,600 (sharp decline in revenue)
The drop in February suggests possible seasonal effects or operational challenges requiring further investigation.

* Average Revenue Per Transaction
February: ₦4,912.82 (highest, despite lowest total revenue)
December: ₦4,567.90
January: ₦4,507.69
The higher February average indicates fewer but higher-value purchases, suggesting price adjustments or premium purchases.
# Customer Insights
* Top 5 Spending Customers
Rebecca Yu (₦51,400), followed by Andrew Robbins (₦51,000), showing strong purchasing power.
Other high-spenders:
Erin Rhodes (₦48,100)
Lisa Logan (₦46,200)
Derek Powell (₦44,100)
These customers are ideal targets for loyalty programs and personalized offers.

* Customer Location Analysis
Ikeja (136 customers) had the highest number of customers, showing strong market presence.
Lekki (108) and Victoria Island (105) followed closely, indicating strong engagement in affluent areas.
Yaba (77) and Surulere (74) show potential for market expansion.

# Sales Trends and Customer Segmentation
* Revenue Breakdown by Age Group
** Mid Adults (₦913,000) generate the highest revenue, making them the primary target segment.
** Older Adults (₦661,500) and Young Adults (₦657,700) also contribute significantly.
** Pre-Retirement (₦53,600) records the lowest revenue, indicating a smaller customer base.
Targeted marketing should focus on Mid and Older Adults while exploring ways to engage Pre-Retirement customers.

* Peak Sales Days
** Saturday (₦4,879.27) and Thursday (₦4,863.01) had the highest average sales, indicating peak shopping days.
** Tuesday (₦4,138.24) and Sunday (₦4,328.17) had the lowest sales.
Promotional strategies can be introduced on low-sales days to boost sales.

# Payment Method Preferences
** Bank Transfers (182 transactions) were the most preferred payment method, showing trust in digital payments.
** Cash (160 transactions) remains popular, highlighting a mix of digital and traditional payment preferences.
** POS (158 transactions) was slightly less used but still significant.
Ensuring seamless digital payment options while maintaining cash acceptance enhances customer convenience.

# Recommendations & Actionable Insights
* Product Optimization:
Focus on promoting top-selling items.
Implement targeted marketing for low-performing products to boost sales.

* Seasonal and Trend Analysis:
Investigate the decline in February sales and adjust strategies accordingly.
Introduce promotions or discounts during low-sales periods.

* Customer Engagement:
Introduce loyalty programs for top-spending customers.
Develop marketing strategies for different age groups, focusing on Mid Adults.

* Location-Based Marketing:
Expand reach in Ikeja, Lekki, and Victoria Island.
Increase marketing efforts in Yaba and Surulere to attract more customers.

* Optimizing Payment Methods:
Promote seamless digital payment options to enhance customer experience.
Maintain a balance between cash and digital transactions.

# Conclusion
The insights derived from python analysis provide a clear roadmap for Naija Tastes Restaurant to optimize sales, improve customer experience, and enhance profitability. Implementing the recommended strategies will help drive growth and sustain customer engagement.
