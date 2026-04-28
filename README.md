# Credit Card Financial Dashboard 

## Project Overview
This project provides a comprehensive analysis of credit card operations, focusing on weekly performance metrics, customer demographics, and transaction patterns. By leveraging **Power BI** and **SQL**, the dashboard enables stakeholders to monitor key performance indicators (KPIs) like total revenue, transaction volume, and interest earned in real-time.


## Objectives
* **Weekly Performance Tracking:** Monitor revenue and transaction trends on a week-over-week (WoW) basis.
* **Customer Segmentation:** Analyze spending patterns across various demographics including age, gender, and income levels.
* **Operational Insights:** Identify high-performing card categories (Blue, Silver, Gold, Platinum) and transaction methods (Swipe, Chip, Online).

## Tech Stack
* **Visualization:** Power BI Desktop
* **Data Processing:** SQL (Data Ingestion & Transformation)
* **Statistical Analysis:** DAX (Data Analysis Expressions)
* **Source Data:** CSV (Transaction and Customer datasets)

## Key Insights (Current Report)
* **Total Revenue:** ₹57M
* **Total Interest:** ₹8M
* **Total Transaction Amount:** ₹46M
* **Top Contributing State:** Gujarat, Maharashtra, and Uttar Pradesh are among the leading regions.
* **Gender Contribution:** Male customers contribute approximately ₹31M in revenue, while Female customers contribute ₹26M.
* **Card Performance:** The "Blue" card category accounts for the majority of transactions (approx. 93% of total revenue).

## DAX Measures Used
To provide dynamic insights, the following measures were implemented:

* **Age Group & Income Group:** Segmenting customers into 'Low', 'Medium', and 'High' categories.
* **Revenue Metrics:**
    $$\text{Current Week Revenue} = \text{SUM}(\text{Sales}[Amount])$$
* **WoW Growth:** Calculated using current vs. previous week comparisons to track performance fluctuations.

## Project Structure
```text
├── Data/
│   ├── CreditCard.csv          # Transaction level data
│   └── Customer.csv            # Demographic data
├── Dashboard/
│   └── Credit_Card_Dashboard.pbix  # Power BI file
├── SQL_Queries/
│   └── data_ingestion.sql      # SQL scripts for database setup
└── README.md
```

## How to Use
1.  **Database Setup:** Import the `CreditCard.csv` and `Customer.csv` files into your SQL environment using the provided scripts.
2.  **Power BI Connection:** Open the `.pbix` file and update the data source settings to point to your local files or SQL server.
3.  **Interaction:** Use the slicers on the left (Gender, Age Group, Income) to filter the visual reports dynamically.

## Dashboard
### 1. Customer Report
![image alt](https://github.com/vnandini879/Credit-card-analysis/blob/fb3bccad1ef366ef0193c0dee7e5e3dbd9ab4d00/credit%20card%20transation.png)

*Focuses on demographics: Age groups, job types, and marital status vs. revenue.*

### 2. Transaction Report
![image alt](https://github.com/vnandini879/Credit-card-analysis/blob/bb6d18627e43615f7fcf0e82e569cac3d1a28bce/Transaction%20report.png)

*Focuses on operational metrics: Card types, expense categories, and weekly revenue trends.*

---

### Author
**Nandini Verma**
*Data Analyst*
[GitHub](https://github.com/vnandini879) | [LinkedIn](https://www.linkedin.com/in/Analyst-kashishagrawal/)
