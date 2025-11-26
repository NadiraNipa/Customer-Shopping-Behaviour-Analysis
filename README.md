#Customer Shopping Behaviour Analysis#

This project analyzes customer purchasing patterns to uncover insights into product preferences, spending behavior, and customer segments. It combines Python, MySQL, and Power BI to perform end-to-end data cleaning, exploratory data analysis, SQL-based business insights, and dashboard visualization.

📊 **Project Overview**

This project explores customer shopping behavior using a dataset of 3,900 transactions. The analysis focuses on:

+ Demographic patterns
+ Spending distribution
+ Product popularity
+ Discount usage
+ Subscription trends
+ Customer segmentation
+ Revenue performance by age, gender, and category

🛠 **Tools & Technologies**

+ Python (Pandas, NumPy, Matplotlib/Seaborn, SQLAlchemy)
+ Jupyter Notebook
+ MySQL (Database integration + business queries)
+ Power BI (Interactive dashboard)

📁 **Project Workflow**
1. Data Cleaning & Preparation (Python)

+ Loaded and explored the dataset
+ Standardized column names
+ Handled missing values (median imputation for review ratings)
+ Performed feature engineering (age grouping, purchase frequency calculation)
+ Removed redundant fields
+ Exported cleaned dataset to MySQL

2. Business Analysis (MySQL)

  Key SQL insights include:
+ Revenue by gender
+ Spending comparison: subscribers vs. non-subscribers
+ Top high-rated products
+ Discount-dependent items
+ Shipping type performance
+ Customer segmentation (New / Returning / Loyal)
+ Revenue by age group

3. Visualization (Power BI)

  Interactive dashboard includes:

+ Total revenue
+ Category-wise performance
+ Customer segments
+ Top-rated & best-selling products
+ Subscription analysis

📈 **Power BI Dashboard**

  Screenshots and the .pbix file are included in the repository.

🧠 **Key Insights**

+ Female customers generated slightly higher average revenue
+ Discounted items attracted high spenders
+ Subscribers demonstrated higher long-term value
+ Age groups 25–40 contributed the largest share of revenue
+ Express shipping users tended to spend more per order

🌟 **Business Recommendations**

+ Promote subscription benefits to increase retention
+ Strengthen loyalty programs for returning customers
+ Highlight top-rated products in marketing campaigns
+ Reassess discount strategy for optimal margins
+ Focus promotions on high-value age groups

🙏 **Credits**

This project was inspired by a YouTube tutorial on customer shopping behavior analysis.
All code has been fully rewritten, adapted, and implemented using MySQL instead of PostgreSQL, with independent visualizations and workflow enhancements.
