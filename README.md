# European Fashion E-commerce — Data Analysis Project

This repository contains a complete data analysis of a European fashion e-commerce dataset.  
It includes data curation, exploratory data analysis (EDA), and interactive Tableau dashboards.

##  Project Overview
- **Goal:** Understand sales performance, discount effectiveness, and customer behavior.
- **Dataset:** European fashion store transactions (cleaned and merged in `Master_final.xlsx`)
- **Tools:** Python (Pandas, Matplotlib), Excel, Tableau

##  Repository Structure
data/         → cleaned dataset files
notebooks/    → Python notebooks for data analysis
tableau/      → Tableau dashboards (.twbx)
docs/         → final report, scope, and project documentation
images/       → charts and screenshots used in presentation
##  Key Findings
- Germany and France lead in total revenue.
- Discounts have limited effect on overall sales.
- Age group **36–45** generates the highest revenue.
- Online purchases (web) slightly outperform mobile app sales.

##  Dashboards
1. **Sales Overview** — KPIs, Revenue by Country & Category  
2. **Discount & Behavior** — Revenue vs Discount, Avg Discount by Country, Age & Channel

## Tools Used
- Python (Pandas, Matplotlib, Seaborn)
- Excel (Pivot Tables, Charts)
- Tableau (Dashboards & KPIs)

##  How to Reproduce
1. Clone the repo  
   ```bash
   git clone https://github.com/s-dandres/european-fashion-ecommerce.git
	2.	Open notebooks/ in JupyterLab or VS Code.
	3.	Load the data from data/Master_final.xlsx.
	4.	Open Tableau workbooks under tableau/.
