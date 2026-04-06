# Deskify-Analysis

## Project Overview
This project involves a comprehensive analysis of sales and financial performance for **Deskify Office Supply Co.**, a retail provider operating across multiple regions. The goal was to transform raw transactional data into actionable insights regarding profitability, shipping efficiency, and product performance to help optimize business operations.

## Key Objectives
- Identify the most and least profitable product categories and sub-categories.
- Analyze regional sales performance to identify high-growth areas.
- Evaluate the impact of shipping modes and discounts on overall profit margins.
- Develop an interactive dashboard for real-time performance tracking.

## Dataset Description
The dataset contains over 8,000 transaction records with the following key attributes:
- **Order Details:** Order ID, Date, Priority, and Quantity.
- **Financials:** Sales, Unit Price, Profit, Discount, and Shipping Cost.
- **Geography:** Region, Country, State, and City.
- **Product Information:** Category (Furniture, Office Supplies, Technology), Sub-Category, and Product Name.

## Tools Used
- **Excel:** Data Cleaning, Pivot Tables, and Advanced Formulas.
- **Data Visualization:** Interactive Dashboard design using Slicers and Timelines.
- **GitHub:** Documentation and Project Hosting.

## Data Analysis Process

### 1. Data Cleaning & Preparation
- Handled missing values in shipping and postal code fields.
- Standardized date formats to enable year-over-year and monthly trend analysis.
- Validated numerical consistency between `Unit Price`, `Quantity`, `Discount`, and `Total Sales`.

### 2. Pivot Table Analysis
I utilized Pivot Tables to aggregate data across multiple dimensions:
- **Total Sales vs. Profit:** Calculated the overall profit margin (approx. 9.8%).
- **Regional Breakdown:** Compared performance across regions such as Ontario, Prairie, and the Northwest Territories.
- **Product Performance:** Identified top-selling products like "Bush Birmingham Collection Bookcase" and "Xerox 1971".

### 3. Key Findings
- **Profitability:** Total sales reached over **$15.5M** with a total profit of **$1.52M**.
- **Shipping Impact:** Analyzed the cost-to-profit ratio of different shipping modes (Regular Air vs. Delivery Truck).
- **High-Value Regions:** Ontario and the Prairie region emerged as the strongest contributors to both revenue and profit.
- **Discount Sensitivity:** Identified a correlation between high discount rates (averaging ~5%) and decreased profit margins in specific "Furniture" sub-categories.

## Interactive Dashboard
The final phase of the project was the creation of a **Financial and Sales Performance Dashboard**. 
<img width="1309" height="618" alt="Screenshot (96)" src="https://github.com/user-attachments/assets/62a3b675-8145-4c80-8bd2-32001b456c5b" />


**Features include:**
- **Dynamic Slicers:** Filter by Region, Product Category, and Order Priority.
- **KPI Cards:** Instant view of Total Sales, Total Profit, and Average Discount.
- **Trend Charts:** Monthly sales performance to identify seasonal peaks.

## Recommendations
Optimize Furniture Shipping:** Review shipping costs for heavy furniture items in the "West" and "Atlantic" regions where margins are thinner.
2. **Discount Strategy:** Reduce the maximum discount threshold for low-margin Office Supplies to protect the bottom line.
3. **Inventory Management:** Increase stock levels for high-performing technology and office supply products identified in the top 10 list.

---

### How to Navigate this Repository

- `Deskify_Analysis_Workbook.xlsx`: The full Excel file including Pivot Tables and the interactive Dashboard.
- `README.md`: Project summary and findings.
