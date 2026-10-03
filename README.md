📊 Customer Shopping Behavior — Data Analytics Project
📌 Overview

This project analyzes customer shopping behavior using Python, PostgreSQL, SQL, and Power BI.

The goal is to transform raw customer data into meaningful insights through data cleaning, exploratory data analysis (EDA), SQL analysis, and interactive dashboarding.

The project demonstrates an end-to-end data analytics workflow, from raw dataset to business insights and visualization.

📂 Dataset

The project uses a Customer Shopping Behavior dataset containing information about customer demographics, shopping patterns, purchase details, and spending behavior.

Key data areas include:
Customer demographics
Purchase categories
Purchase amount
Discounts and subscriptions
Payment methods
Shopping frequency
Customer ratings
Previous purchase behavior
🛠️ Tools & Technologies
Tool	Purpose
Python	Data cleaning and exploratory data analysis
Pandas	Data manipulation and analysis
Jupyter Notebook	Python-based analysis
PostgreSQL	Data storage and SQL analysis
SQL	Data querying and business analysis
Power BI	Interactive dashboard and visualization
Excel/CSV	Dataset and supporting analysis
🔄 Project Workflow

The project follows an end-to-end analytics workflow:

Raw Dataset → Python EDA → Data Cleaning → PostgreSQL → SQL Analysis → Power BI Dashboard → Report & Insights

🧩 Project Sessions
1. Data Loading & Exploration — Python

The dataset is first loaded into Python using Pandas.

Initial analysis includes:

Understanding the dataset structure
Checking rows and columns
Identifying data types
Checking missing values
Identifying duplicate records
Understanding numerical and categorical variables
Generating basic statistical summaries
2. Exploratory Data Analysis (EDA)

EDA is performed to understand customer behavior and identify patterns in the data.

Key analysis includes:

Customer spending patterns
Purchase frequency
Category-wise sales
Customer demographics
Discount usage
Subscription behavior
Payment method distribution
Customer ratings

Python libraries such as Pandas, NumPy, and Matplotlib/Seaborn can be used for analysis and visualization.

3. Data Cleaning

The raw dataset is cleaned and prepared for further analysis.

Data preparation includes:

Handling missing values
Removing duplicate records
Correcting data types
Standardizing column names
Checking inconsistent values
Creating derived columns where required
Preparing clean data for PostgreSQL and Power BI

The cleaned dataset is then loaded into a PostgreSQL database.

4. PostgreSQL & SQL Analysis

The cleaned data is stored in PostgreSQL for structured querying and analysis.

SQL queries are used to answer business-related questions such as:

What are the highest-selling product categories?
Which customer segments generate the most revenue?
What is the average purchase amount?
How does subscription status affect spending?
Which products receive the highest ratings?
Which payment methods are most commonly used?
What are the purchasing patterns of different customer groups?

The SQL analysis helps convert raw data into actionable business insights.

5. Power BI Dashboard

The analyzed data is connected to Power BI to create an interactive dashboard.

Dashboard includes:
Total Revenue
Total Customers
Average Purchase Amount
Purchase Count
Category-wise Sales
Customer Segmentation
Subscription Analysis
Payment Method Analysis
Customer Rating Analysis
Interactive filters and slicers

The dashboard provides a visual overview of customer purchasing behavior and key performance indicators.

📊 Dashboard

The Power BI dashboard provides an interactive view of the major findings from the analysis.

Key dashboard sections:

Customer Overview

Total customers
Average purchase value
Customer demographics

Sales Analysis

Revenue by category
Purchase trends
Product performance

Customer Behavior

Purchase frequency
Subscription behavior
Discount usage

Payment & Rating Analysis

Payment method distribution
Customer ratings
Category-level performance

Add your Power BI dashboard screenshot here.

![Power BI Dashboard](images/dashboard.png)
📈 Results & Insights

The analysis provides insights into:

Customer purchasing behavior
High-performing product categories
Spending patterns across customer segments
Relationship between subscriptions and purchasing behavior
Discount and promotional trends
Popular payment methods
Customer satisfaction based on ratings

These insights can help businesses understand customer behavior and support data-driven decision-making.

📁 Project Structure
customer-shopping-behavior-analysis/
│
├── data/
│   └── customer_shopping_behavior.csv
│
├── notebooks/
│   └── customer_behavior_analysis.ipynb
│
├── sql/
│   └── customer_behavior_queries.sql
│
├── powerbi/
│   └── customer_behavior_dashboard.pbix
│
├── images/
│   └── dashboard.png
│
├── report/
│   └── customer_behavior_report.pdf
│
└── README.md
▶️ How to Run
Step 1 — Clone the Repository
git clone <your-github-repository-url>
cd customer-shopping-behavior-analysis
Step 2 — Install Python Libraries
pip install pandas numpy matplotlib seaborn sqlalchemy psycopg2-binary
Step 3 — Run the Python Notebook

Open the Jupyter Notebook:

jupyter notebook

Run the notebook to:

Load the dataset
Explore the data
Clean the data
Perform EDA
Prepare the dataset for PostgreSQL
Step 4 — Set Up PostgreSQL

Create a PostgreSQL database and configure the database connection in Python.

Example:

from sqlalchemy import create_engine

engine = create_engine(
    "postgresql+psycopg2://username:password@localhost:5432/customer_behavior"
)

Load the cleaned dataset into PostgreSQL:

df.to_sql(
    "customer",
    engine,
    if_exists="replace",
    index=False
)
Step 5 — Run SQL Queries

Open the SQL file:

sql/customer_behavior_queries.sql

Run the queries in PostgreSQL / pgAdmin to perform business analysis.

Step 6 — Open Power BI

Open:

powerbi/customer_behavior_dashboard.pbix

Refresh the data connection if required and explore the interactive dashboard.

🎯 Skills Demonstrated

This project demonstrates practical experience in:

Python
Pandas
Exploratory Data Analysis
Data Cleaning
SQL
PostgreSQL
Data Transformation
Power BI
Data Visualization
Business Analysis
Dashboard Development
Data-driven Insights
👤 Author

Thejaswi

Data Analytics | Python | SQL | PostgreSQL | Power BI
