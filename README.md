# Customer-Behavior-Dashboard
In this project, I analyzed 3,900 customer transactions to uncover insights into spending behavior, product performance, and subscription impact. Using Python (Pandas) and SQL, I performed data cleaning, exploratory data analysis, and aggregation to identify trends related to shipping type, discounts, and seasonal purchasing patterns.

# Customer Shopping Behavior Analysis

##  Project Overview

This project analyzes customer shopping behavior using transactional data to uncover insights into spending patterns, customer preferences, subscription impact, and seasonal trends. The goal is to support data-driven decision-making for marketing, customer retention, and business strategy.

The project includes data cleaning and exploratory data analysis (EDA) in Python, SQL-based analysis in PostgreSQL, and dashboard visualization in Power BI.

---

##  Dataset

- Total Records: 3,900 transactions
- Total Features: 18 columns

### Key Features:
- Customer Demographics: Age, Gender, Location, Subscription Status
- Purchase Details: Item Purchased, Category, Purchase Amount, Season, Size, Color
- Behavioral Data: Discount Applied, Promo Code Used, Previous Purchases, Frequency of Purchases, Review Rating, Shipping Type

### Data Cleaning:
- Handled 37 missing values in Review Rating
- Checked duplicates
- Verified data types
- Performed data validation and formatting

---

##  Tools & Technologies

- Python (Pandas, NumPy, Matplotlib/Seaborn)
- SQL (PostgreSQL)
- Power BI
- Jupyter Notebook
- Git & GitHub

---

##  Project Steps

### 1️⃣ Data Loading & Cleaning (Python)
- Imported dataset using pandas
- Used `df.info()` and `df.describe()` for initial exploration
- Handled missing values
- Checked for inconsistencies and duplicates

### 2️⃣ Exploratory Data Analysis (EDA)
- Analyzed average purchase amount by category
- Compared subscription vs non-subscription spending
- Evaluated seasonal sales patterns
- Examined shipping type impact on revenue
- Analyzed discount and promo code effectiveness

### 3️⃣ SQL Analysis (PostgreSQL)
- Created database and imported cleaned dataset
- Performed aggregation queries using:
  - GROUP BY
  - AVG()
  - SUM()
  - COUNT()
  - ROUND()
- Extracted insights for business reporting

### 4️⃣ Dashboard (Power BI)
- Built interactive dashboard showing:
  - Revenue by Category
  - Seasonal Trends
  - Subscription Impact
  - Shipping Type Analysis
- Enabled filtering by customer demographics

### 5️⃣ Reporting
- Created summary report highlighting key insights
- Prepared PowerPoint presentation for business stakeholders

---

##  Key Insights

- Subscription customers showed higher average spending.
- Express shipping users had higher purchase amounts compared to standard shipping.
- Seasonal trends influenced category performance.
- Discounts increased purchase frequency but impacted average order value.
- High-frequency customers contributed significantly to total revenue.

---

##  How to Run the Project

### Step 1: Clone the Repository
```bash
git clone https://github.com/your-username/your-repo-name.git
