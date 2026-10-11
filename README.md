# Task-2-Exploratory_Data_Analysis
*Exploratory Data Analysis(EDA) using Excel — descriptive statistics, product performance, sales trends, and outlier analysis.*

## Project Overview
This project was completed as part of my Week 2 data analytics internship assignment. The objective was to explore a dataset, calculate descriptive statistics, identify patterns and trends, detect outliers, and summarise key findings using Microsoft Excel.

## Objectives
- Calculate basic descriptive statistics, including count, mean, and median.
- product performance using order counts, quantities, and total revenue.
- Examine recorded sales trends over time.
- Identify potential outliers using the Interquartile Range (IQR) method.
- Interpret findings and communicate insights.

## Dataset

The dataset was provided for this internship project.
The analysis focused on descriptive statistics, product performance,
yearly trends, and outlier detection.
The dataset contains:

* 1,200 order records
* 14 columns
* Order data

The dataset contains information about:

* Orders
* Customers
* Products
* Quantity and pricing
* Shipping
* Payment methods
* Order status
* Tracking information
* Cart information
* Coupon usage
* Referral sources
  
## Tools Used
- Microsoft Excel
- PivotTables
- Excel formulas
- Descriptive statistics
- Interquartile Range (IQR) method
  
## Analysis Performed
* **Descriptive Statistics:** Calculated the count, mean, median, minimum, and maximum for selected numerical variables.
<img width="1343" height="732" alt="EDA Analysis" src="https://github.com/user-attachments/assets/9b655aec-2965-4834-a571-6c1bebfb688b" />

* **Product Performance:** Compared products by order count, quantity sold, and total revenue.

* **Trend Analysis:** Examined yearly order counts and revenue while accounting for the fact that 2025 contains only January–June data.

* **Outlier Analysis:** Used the IQR method to identify unusually high TotalPrice observations. Eight observations exceeded the upper outlier threshold of 3,330.4075.
These observations were retained because the recorded total prices were consistent with quantity multiplied by unit price, and no clear evidence of calculation errors was identified.
<img width="1019" height="725" alt="Outlier Analysis" src="https://github.com/user-attachments/assets/7f0b7d55-0a29-48a6-a18c-82b9baa776c2" />


## Key Findings
- Printer recorded the highest number of orders, with 181.
- Chair generated the highest total revenue, at approximately 195,620.11.
- Phone recorded the lowest order count of 156 and revenue of 151,722.39 among the seven products.
- Eight TotalPrice observations were identified as potential outliers.
- The mean TotalPrice was higher than the median, suggesting that higher-value orders influenced the average.
- The partial-year coverage of 2025 limits direct comparisons with full-year figures.

## Recommendations
- **Improve Product Performance:** Investigate the factors influencing product sales and revenue, including pricing and customer demand. This will help identify opportunities to improve the performance of products with lower sales.
- **Investigate Revenue Trends:** Revenue declined from 2023 to 2024. Review historical sales performance to identify possible reasons for the decrease and develop strategies to improve revenue. Note that 2025 covers only January to June, so its revenue should not be directly compared with full-year figures.
- **Monitor High-Value Orders:** Review the eight outlier orders with unusually high total prices to confirm that their quantities and unit prices are accurate. Since the calculations are consistent, retain these orders unless further investigation reveals errors.
- **Investigate Low-Performing Products:** Phone recorded the lowest order count and revenue among the products analysed. Examine its pricing, demand, and sales patterns to identify possible reasons for its lower performance and determine whether improvements are needed.
- **Monitor Sales Performance Regularly:** Track order counts, product revenue, quantities sold, and changes in sales over time. Regular monitoring will help identify emerging trends, detect unusual transactions, and support better business decisions.
## Skills Demonstrated
- Data Cleaning and Preparation
- Descriptive Statistics
- Exploratory Data Analysis(EDA)
- Pivot Table Analysis
- Outlier Detection
- Data Interpretation
- Microsoft Excel
- Analytical Thinking
## Conclusion
This project helped me practise data exploration, descriptive statistics, PivotTables, outlier detection, and communicating analytical findings using Excel.
