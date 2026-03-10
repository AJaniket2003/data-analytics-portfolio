🛍 Customer Behavior Analysis
An end-to-end data analytics project that analyzes retail customer behavior and converts raw transactional data into actionable business insights using Python, SQL, and Power BI.
This project demonstrates the complete analytics workflow used by data analysts in real business environments.
________________________________________
📊 Dashboard Preview
 ________________________________________
🎯 Business Problem
Retail companies collect large volumes of customer transaction data, but without proper analysis it is difficult to understand:
•	Which customers generate the most revenue
•	Which product categories drive sales
•	How customer demographics affect purchasing behavior
This project analyzes customer data to uncover key revenue drivers and customer segments.
________________________________________
🛠 Tech Stack
Data Processing
•	Python
•	Pandas
•	NumPy
Data Analysis
•	SQL
Data Visualization
•	Power BI
________________________________________
📂 Project Workflow
1️. Data Cleaning (Python)
The raw dataset was cleaned and prepared using Python.
Tasks performed:
•	Removed duplicate records
•	Handled missing values
•	Standardized categorical data
•	Prepared dataset for SQL analysis
Libraries used:
Pandas, NumPy
________________________________________
2️. Business Analysis (SQL)
SQL queries were used to generate key business insights:
•	Revenue by product category
•	Customer segmentation
•	Sales by age group
•	Average purchase value
Example query:
SELECT category, SUM(purchase_amount) AS revenue
FROM sales
GROUP BY category
ORDER BY revenue DESC;
________________________________________
3️. Data Visualization (Power BI)
An interactive Power BI dashboard was built to help stakeholders quickly understand customer behavior.
Key Dashboard Features
✔ Customer KPI metrics
✔ Revenue by category
✔ Customer segmentation
✔ Age group purchasing trends
Interactive Filters
•	Gender
•	Season
•	Subscription Status
•	Shipping Type
______________________________________
📊 Key Metrics
Metric	Value
Customers Analyzed	3,900+
Average Purchase Value	$59.76
Top Category Revenue	$104K
Subscription Rate	27%
________________________________________
📈 Key Insights
Customer Segmentation
•	Loyal customers → 79.9%
•	Returning customers → 17.97%
•	New customers → 2.13%
Revenue Insights
Top performing categories:
1️. Clothing — $104K
2️. Accessories — $74K
3️. Footwear — $36K
4️. Outerwear — $19K
Customer Trends
•	Young adults generate the highest revenue
•	Middle-aged customers have strong purchase frequency

________________________________________
💡 Business Recommendations
Based on the analysis:
✔ Increase marketing focus on young adult customers
✔ Promote clothing category bundles
✔ Improve subscription adoption (currently 27%)
________________________________________
📁 Repository Structure
customer-behavior-analysis
│
├── data
├── notebooks
├── sql
├── dashboard
├── images
└── README.md
________________________________________
🚀 Future Improvements
•	Customer lifetime value analysis
•	RFM customer segmentation
•	Predictive sales forecasting
•	Advanced Power BI DAX metrics
________________________________________
👤 Author
Aniket Jaiswal
Data Analyst Portfolio Project
Python | SQL | Power BI | Data Visualization
