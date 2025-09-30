Introduction
This project analyzes customer demographics, household profiles, and purchasing behavior to uncover what drives marketing campaign acceptance in the U Food Marketing dataset. Using Python and exploratory data analysis (EDA), the notebook highlights key trends and provides actionable marketing recommendations.
📂 Dataset
File: u_food_marketing.csv
Key features include:
Demographics: Age, marital status, education, number of children
Purchasing Behavior: Web, catalog, and store purchases
Marketing Response: Acceptance across multiple campaigns
⚙️ Methods
Data Cleaning & Feature Engineering
Removed duplicates and handled categorical dummies
Created new variables (Total_Children, Marital_Status, Education_Status, Accepted_Campaigns)
Exploratory Data Analysis (EDA)
Pearson correlation analysis
Visualizations with Seaborn & Matplotlib
Age segmentation and purchasing channel comparisons
Segmentation Dimensions
Age groups (23–30, 31–40, …, 71–85)
Household size (children)
Marital status categories
Education levels
🔍 Key Findings
Customers aged 31–70 spend the most, but have lower campaign acceptance.
Younger (23–30) and older (71+) customers accept campaigns more often, but spend less.
Catalog purchases are strong predictors of campaign acceptance.
Fewer children → higher likelihood of campaign acceptance.
Married, single, and together customers spend more compared to divorced/widowed.
🎯 Recommendations
Split Marketing Focus
Use catalogs to boost acceptance
Maintain web/in-store presence for higher volume
Target Demographics
Focus on 31–70 for high spend
Tailor campaigns for 23–30 and 71+ who are more responsive
Household Segmentation
Prioritize smaller households with fewer children
Marital Status Strategy
Focus on Married, Single, and Together groups
🛠️ Tools & Libraries
Python (Pandas, NumPy)
Seaborn, Matplotlib (visualization)
Jupyter Notebook
