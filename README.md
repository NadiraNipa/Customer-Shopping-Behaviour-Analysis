# Customer-Shopping-Behaviour-Analysis
This project analyzes customer purchasing patterns to uncover insights into product preferences, spending behavior, and customer segments. It combines Python, MySQL, and Power BI to perform end-to-end data cleaning, exploratory data analysis, SQL-based business insights, and dashboard visualization.

📊 Project Overview

The goal of this project is to explore customer shopping behavior using a dataset of 3,900 transactions. The analysis focuses on:

Demographic patterns

Spending distribution

Product popularity

Discount usage

Subscription trends

Customer segmentation

Revenue performance by age, gender, and category

🛠 Tools & Technologies

Python (Pandas, NumPy, Matplotlib/Seaborn, SQLAlchemy)

MySQL (Database integration + business queries)

Power BI (Interactive dashboard)

Jupyter Notebook

📁 Project Workflow
1. Data Cleaning & Preparation (Python)

Loaded and explored dataset

Standardized column names

Handled missing values (median imputation for review ratings)

Feature engineering (age grouping, purchase frequency calculation)

Removed redundant fields

Exported cleaned dataset to MySQL

2. Business Analysis (MySQL)

Performed SQL queries to extract insights such as:

Revenue by gender

Average spend by subscribers vs. non-subscribers

Top high-rated products

Discount-dependent items

Shipping type comparisons

Customer segmentation (New / Returning / Loyal)

Age-group revenue contribution

3. Visualization (Power BI)

Created an interactive dashboard highlighting:

Total revenue

Category-wise performance

Customer segments

Ratings & top products

Subscription analysis

📈 Power BI Dashboard

Screenshots and the .pbix file are included in the repository.

📂 Repository Structure
├── data/              # Dataset (raw & cleaned)
├── notebooks/         # Python notebooks for EDA & cleaning
├── sql/               # MySQL queries
├── dashboard/         # Power BI files
├── images/            # Visualizations/screenshots
└── README.md          # Project documentation

🧠 Key Insights

Female customers generated slightly higher average revenue.

Products with discounts still attracted high spenders.

Subscribers showed stronger long-term purchasing behavior.

Age groups 25–40 contributed the largest share of revenue.

Express shipping users tended to spend more per order.

🌟 Business Recommendations

Promote subscription benefits to increase retention

Enhance loyalty programs for returning customers

Feature top-rated products in marketing campaigns

Review discount strategies for revenue optimization

Target high-value age groups with focused promotions

🙏 Credits

This project was inspired by a YouTube tutorial on customer shopping behavior analysis.
All code has been fully rewritten, adapted, and implemented using MySQL instead of PostgreSQL, with independent visualizations and workflow improvements.
