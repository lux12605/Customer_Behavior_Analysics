
# 🛒 Customer Shopping Behavior Analysis

## 📌 Project Overview

This project analyzes **customer shopping behavior** to understand purchasing patterns, customer preferences, product performance, and sales trends.

The project uses **Python, SQL Server, and Power BI** to perform data cleaning, exploratory data analysis, SQL-based analysis, and interactive dashboard visualization.

The main objective is to transform raw customer shopping data into meaningful business insights that can support data-driven decision-making.

---

## 🎯 Objectives

- Analyze customer purchasing behavior.
- Identify popular product categories and products.
- Understand customer spending patterns.
- Analyze customer demographics and purchase trends.
- Study relationships between ratings, discounts, and purchases.
- Perform SQL queries to extract useful business insights.
- Create an interactive Power BI dashboard.
- Present analytical findings in a simple and understandable way.

---

## 🗂️ Dataset

The project uses the **Customer Shopping Behavior Dataset**.

The dataset contains customer-level shopping information such as:

- Customer ID
- Age
- Gender
- Category
- Item Purchased
- Purchase Amount
- Location
- Size
- Color
- Season
- Review Rating
- Subscription Status
- Payment Method
- Shipping Type
- Discount Applied
- Previous Purchases
- Frequency of Purchases

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| 🐍 Python | Data cleaning and analysis |
| 🐼 Pandas | Data manipulation |
| 📊 Matplotlib | Data visualization |
| 🗄️ SQL Server | Database storage and SQL analysis |
| 📈 Power BI | Interactive dashboard |
| 📓 Jupyter Notebook | Python analysis |
| 🔧 Git & GitHub | Version control and project sharing |

---

## 🔄 Project Workflow

```text
Raw Dataset
     ↓
Data Cleaning
     ↓
Exploratory Data Analysis
     ↓
SQL Server Database
     ↓
SQL Queries & Business Analysis
     ↓
Power BI Dashboard
     ↓
Business Insights
```

---

## 🐍 Python Data Analysis

Python and Pandas were used to clean and preprocess the dataset.

### Data preprocessing included:

- Checking missing values
- Handling missing values
- Removing duplicate records
- Checking data types
- Renaming columns where required
- Creating useful derived columns
- Categorizing customer age groups
- Performing exploratory data analysis

Example:

```python
import pandas as pd

df = pd.read_csv("customer_shopping_behavior.csv")

print(df.head())
print(df.info())
print(df.isnull().sum())
```

---

## 🗄️ SQL Server Analysis

The cleaned dataset was loaded into **Microsoft SQL Server** for database-based analysis.

SQL was used to answer business questions such as:

- What are the most popular product categories?
- Which products generate the highest purchase amounts?
- What is the average purchase amount?
- Which customers have made the most purchases?
- How does customer behavior vary by gender?
- Which payment methods are most commonly used?
- How do discounts affect purchases?
- Which categories have the highest average ratings?

---

## 📊 Power BI Dashboard

Power BI was used to create an interactive dashboard for visualizing customer shopping behavior.

### Dashboard analysis includes:

- Total customers
- Total purchases
- Purchase amount
- Average purchase amount
- Product category analysis
- Gender-wise analysis
- Age-group analysis
- Customer subscription analysis
- Payment method analysis
- Seasonal shopping trends
- Product ratings
- Discount usage

The dashboard allows users to interact with the data using filters and visualizations.

---

## 🔍 Key Business Questions

This project focuses on answering questions such as:

1. Which product categories are most purchased?
2. Which products generate the highest revenue?
3. What is the average customer purchase amount?
4. Which age group contributes the most purchases?
5. How does purchasing behavior differ between genders?
6. Which payment methods are most frequently used?
7. What percentage of customers have subscriptions?
8. Does discount usage influence purchasing behavior?
9. Which products receive higher customer ratings?
10. How does purchasing behavior change across seasons?

---

## 📈 Key Insights

The analysis can help businesses understand:

- Customer purchasing patterns
- High-performing product categories
- Customer preferences
- Spending behavior
- Subscription trends
- Payment preferences
- Seasonal purchasing behavior
- Product performance
- Customer satisfaction through ratings

These insights can be used to improve **marketing strategies, product planning, customer retention, and sales decisions**.

---

## 📁 Project Structure

```text
Customer-Shopping-Behavior-Analysis/
│
├── customer_shopping_behavior.csv
│
├── main.ipynb
│
├── customer_behavior.sql
│
├── customer_behavior_Analysis.pbix
│
└── README.md
```

---

## 🚀 How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/customer-shopping-behavior-analysis.git
```

### 2. Install Python Libraries

```bash
pip install pandas matplotlib seaborn jupyter
```

### 3. Open the Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
main.ipynb
```

### 4. SQL Server

Create a database in Microsoft SQL Server and execute:

```text
customer_behavior.sql
```

Load the dataset into the required table and execute the analytical queries.

### 5. Power BI

Open:

```text
customer_behavior_Analysis.pbix
```

Refresh the data source if required and explore the dashboard.

---

## 💡 Skills Demonstrated

- Data Cleaning
- Data Preprocessing
- Exploratory Data Analysis
- Python Programming
- Pandas
- SQL
- Microsoft SQL Server
- Data Visualization
- Power BI
- Dashboard Development
- Business Intelligence
- Business Problem Solving

---

## 🔮 Future Enhancements

- Add customer segmentation using Machine Learning.
- Build a customer churn prediction model.
- Add sales forecasting.
- Develop an automated data pipeline.
- Deploy the dashboard online.
- Add real-time data processing.
- Create recommendation systems based on customer purchasing behavior.

---

## 👨‍💻 Author

**Lakshmanan**

B.E. Computer Science Engineering

Interested in **Data Analytics, Python, SQL, Power BI, and Business Intelligence**.

---

## ⭐ Project

If you find this project useful, consider giving the repository a ⭐ on GitHub.
