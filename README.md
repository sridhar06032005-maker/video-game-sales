# 🎮 Video Game Sales Data Analysis

## 📌 Project Overview
This project analyzes global video game sales data to identify top-selling games, platform performance, genre distribution, and publisher performance.  
The goal is to transform raw sales data into meaningful business insights using SQL, Python, and Power BI.

---

## 🛠 Tools & Technologies Used

- SQL (Data Querying & Aggregation)
- Python (Pandas, NumPy, Matplotlib)
- Power BI (Interactive Dashboard)
- Git & GitHub (Version Control)

---

## 📊 Project Workflow

1. Data Cleaning and Preparation
2. SQL Analysis (Joins, Aggregations, CTEs)
3. Python Data Analysis using Pandas
4. Data Visualization
5. Power BI Dashboard Creation

---

## 🐍 Python Analysis

Used Python for:
- Data cleaning
- Handling missing values
- Aggregations
- Genre-wise & Platform-wise analysis
- Data visualization

### Sample Python Code

```python
import pandas as pd

# Load dataset
df = pd.read_csv("vgsales.csv")

# Top 10 selling games
top_games = df.sort_values(by="Global_Sales", ascending=False).head(10)
print(top_games[["Name", "Global_Sales"]])
