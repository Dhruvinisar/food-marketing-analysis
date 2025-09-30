# 🍽️ U Food Marketing Analysis

## 📌 Overview

This project explores **customer demographics, household profiles, and purchasing behavior** to understand what drives **marketing campaign acceptance** in the U Food Marketing dataset.

Using **Python** and **exploratory data analysis (EDA)**, the notebook uncovers insights into age, family size, marital status, and purchase channels — and how they influence **spending vs. responsiveness to campaigns**.



## 📂 Dataset

* **File:** `u_food_marketing.csv`
* **Key Columns:**

  * 👤 Demographics → Age, marital status, education, children
  * 🛒 Purchases → Web, catalog, in-store transactions
  * 📢 Marketing Response → Acceptance across multiple campaigns


## ⚙️ Workflow

1. **Data Cleaning & Feature Engineering**

   * Removed duplicates
   * Built new features:

     * `Total_Children`
     * `Marital_Status`
     * `Education_Status`
     * `Accepted_Campaigns`

2. **Exploratory Data Analysis (EDA)**

   * Correlation analysis (Pearson)
   * Visualizations (Seaborn, Matplotlib)
   * Segmentation by age, household size, marital status

3. **Segmentation Dimensions**

   * Age groups (23–30, 31–40, …, 71–85)
   * Number of children
   * Marital status categories
   * Education levels

## 🔍 Key Insights

* 💵 **31–70 years old** → spend the most, but accept fewer campaigns
* 👶 **Fewer children** → higher chance of accepting campaigns
* 📚 **Education** → minimal impact on spending/acceptance
* 💍 **Married / Single / Together** → higher spending vs. Divorced / Widowed
* 📦 **Catalog purchases** → strongest link to campaign acceptance

---

## 🎯 Recommendations

✅ **Split strategy**: use catalogs to increase acceptance, but keep investing in web/in-store for higher volume.
✅ **Target demographics**:

* 31–70 → focus for high spend
* 23–30 & 71+ → tailor campaigns for higher responsiveness
  ✅ **Households**: prioritize smaller families (fewer children).
  ✅ **Marital groups**: focus on Married, Single, and Together segments.

---

## 🛠️ Tech Stack

* **Python** → pandas, numpy
* **Visualization** → seaborn, matplotlib
* **Environment** → Jupyter Notebook


## 🚀 How to Run Locally

```bash
# 1. Clone this repository
git clone https://github.com/your-username/u-food-marketing-analysis.git

# 2. Navigate into the folder
cd u-food-marketing-analysis

# 3. Install dependencies
pip install -r requirements.txt

# 4. Launch Jupyter Notebook
jupyter notebook "U Food Marketing analysis.ipynb"


## 📈 Future Enhancements

* 🤖 Build predictive models for campaign acceptance probability
* 🧪 A/B test catalog vs. digital marketing
* 📊 Apply clustering (e.g., K-Means) for advanced segmentation

✍️ **Author:** Dhruvi Nisar
📌 Part of my **Analytics & Data Storytelling Portfolio

