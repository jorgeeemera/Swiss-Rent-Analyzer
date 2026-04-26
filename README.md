# 🇨🇭 Swiss Rent & Cost of Living Analyzer

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=Tableau&logoColor=white)

## 📌 Project Overview
As an international Software Engineering student at FHNW (Switzerland), I developed this End-to-End Data Analysis project to understand the Swiss real estate market. The goal is to analyze rent prices across different cantons based on living space, rooms, and location.

**👉 [View the Interactive Tableau Dashboard Here](https://public.tableau.com/shared/YC7YDM6W8?:display_count=n&:origin=viz_share_link)**

### 📊 Dashboard Preview
![Swiss Rent Analyzer Dashboard](images/dashboard.jpg)

## 🛠️ The Pipeline (ETL Process)

1. **Extract & Transform (Python/Pandas):** - Cleaned a raw dataset of 1,000+ Swiss apartment listings.
   - Handled missing values, standardized data types, and filtered out anomalies (e.g., listings with < 15 sq meters).
2. **Load & Query (SQLite):** - Designed a relational database to store the clean data.
   - Executed SQL queries with `GROUP BY` and aggregations to find the top most expensive cities (Geneva, Paradiso, Männedorf).
3. **Visualize (Tableau):** - Created an interactive geographical dashboard mapping rent prices (color gradient) and living space (size) across Switzerland.

## 📂 Repository Structure
- `/data`: Raw and cleaned CSV datasets.
- `/notebooks`: Jupyter notebooks (`.ipynb`) containing the EDA and Pandas cleaning process.
- `/sql`: SQLite database and query scripts.

## 💡 Key Insights
- **Geneva** remains the most expensive city in the dataset, with an average rent of over 4,200 CHF for ~100m².
- High concentration of premium real estate along the "Goldküste" (Lake Zurich) and Ticino (Paradiso).