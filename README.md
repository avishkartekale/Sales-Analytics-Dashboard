# Sales-Analytics-Dashboard
Data analytics project showcasing behavior analysis using python, sql and power BI.
📝 Overview

This project demonstrates a complete end-to-end data analytics workflow, starting from importing raw data, exploring and cleaning it in Python, loading the refined dataset into SQL databases, performing analytical SQL queries, and finally building an interactive Power BI dashboard to extract insights.
A summary report and presentation (built using Gamma) are included to make the project industry-ready.

📁 Dataset

Contains customer-level transactional data
Includes fields such as:
Customer demographics
Purchase details
Ratings
Subscription info
Product categories
Payment, shipping, and location data
File format: CSV (≈3900 rows)
You may replace the dataset with your own, as long as the column names remain similar.

🛠 Tools & Technologies Used
Programming
Python (Pandas, NumPy, Matplotlib, Seaborn)
Jupyter Notebook
Databases
PostgreSQL
MySQL
SQL Server
Visualization
Power BI Desktop
Documentation
Gamma.app (PPT Presentation)
Markdown / README

🔍 Project Steps
1. Data Loading (Python)
Imported the raw dataset using Pandas
Verified data types
Checked missing values & duplicates

2. Exploratory Data Analysis (EDA)
Performed:
Summary statistics
Distribution analysis
Correlation heatmaps
Category-wise comparisons
Outlier detection

3. Data Cleaning
Handled missing values
Removed duplicates
Converted data types
Normalized column formats
Cleaned inconsistent text categories

4. SQL Database Integration
Loaded cleaned data into:
PostgreSQL
MySQL
SQL Server
Executed analytical queries including:
Aggregations
Ranking (ROW_NUMBER, RANK)
Joins
Grouping & filtering
Customer segmentation queries

5. Power BI Dashboard
Created an interactive dashboard with:
KPIs:
Total Customers
Average Rating
Average Purchase Amount
Visuals:
Revenue by Category
Sales by Age Group
Subscription Breakdown
Gender Analysis
Shipping Type Preferences
The dashboard provides actionable business insights.

6. Reporting & Presentation
Built a clean project report summarizing key findings
Designed a slick Gamma Presentation for recruiters/interview panels

📊 Dashboard Snapshot
(Add a Power BI screenshot here in your GitHub README)

📈 Key Results & Insights
Identified top-performing product categories
Found the age groups contributing highest revenue
Established subscription vs non-subscription purchase patterns
Analyzed customer purchase frequency and rating behavior
Highlighted revenue drivers & customer segments



🚀How to Run This Project
1. Clone the repository
git clone (https://github.com/avishkartekale/Sales-Analytics-Dashboard/tree/main)
cd project-name

2. Install Python dependencies
pip install -r requirements.txt

3. Run the Jupyter notebook
jupyter notebook

4. Set up SQL Database (Optional)
Create a database in PostgreSQL / MySQL / SQL Server
Import the .csv or use the Python script to load data
Run SQL queries in the SQL script folder

5. Open Power BI Dashboard
Open the .pbix file in Power BI Desktop
Refresh the data source if required

6. View the PPT & Report
Presentation is in the /presentation folder (Gamma exported PPT)
Report PDF is in the /report folder
