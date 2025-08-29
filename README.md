# ☕ Coffee Shop Sales Analysis Dashboard

## 📌 Project Objective
The objective of this project is to analyze and monitor the sales performance of a coffee shop across different coffee types, sizes, and locations.  
It provides insights into revenue trends, customer contributions, and helps in making data-driven business decisions.

---

## 📊 Key Metrics (KPIs)
- **Total Quantity Sold:** 3,551 units  
- **Total Sales:** $45,134  
- **Top 10 Customers Contribution:** 8% of total sales  
- **Sales Distribution by Country:**  
  - United States: 79%  
  - United Kingdom: 15%  
  - Ireland: 6%  
- **Orders by Coffee Type:** Fairly balanced, with Arabica (27%) leading slightly.

---

## 🔎 Key Insights
- Sales peaked in **2021** but dropped noticeably in **2022**
- **Arabica** and **Exclesa** generate the highest sales revenue, despite **Arabica** and **Robusta** being the most ordered coffee types, indicating a potential higher profit margin or pricing advantage for Exclesa.
- **United States dominates** sales (79%), suggesting an opportunity to grow market share in the UK and Ireland.
- **Top 10 customers contribute only 8%** of total sales, indicating a broad customer base rather than dependence on a few clients.

---

## 💡 Recommendations
1. **Boost Sales in 2022 and beyond**  
   Investigate the decline in 2022 sales and introduce marketing campaigns, promotions, or loyalty incentives.

2. **Expand Market Reach**  
   Invest in marketing strategies or localized promotions to grow sales in the **UK** and **Ireland**, where contributions are relatively low.

3. **Enhance Loyalty Programs**  
   While sales are spread across many customers, loyalty programs could turn occasional buyers into repeat customers.

4. **Boost Exclesa Sales with Pricing Analysis and Promotions**  
   Investigate **pricing** or **cost structures** to understand why **Exclesa** yields higher sales despite lower order volume, and consider targeted promotions to increase Exclesa orders while maintaining **Arabica** and **Robusta’s** strong demand.

   ---

## 📂 Dataset
The dataset used for this analysis is included in this repository:  
- <a href="https://github.com/JaySpesh/Coffee-Data-Analysis/blob/main/coffeeOrdersData.xlsx">Dataset</a>

---

## 🛠 Tools Used
- **Excel** – For data modeling and visualization.
- **Pivot Tables:** For summarizing and analyzing sales data.
- **Excel Dashboard:** Interactive visuals with slicers (Year, Roast Type, Size, Loyalty Card).
- **GitHub** – For project documentation and version control.

  ---


## 🧹 Data Cleaning & Transformation Steps
- **Removed empty/extra columns** from the orders dataset.
- **Standardized date and price formats** for consistency.
- **Merged datasets:**
  - Joined `Orders` with `Products` on **Product ID**.
  - Joined the result with `Customers` on **Customer ID**.
- **Added calculated columns:**
  - **Total Sales** = Quantity × Unit Price
  - **Year** = `YEAR([Order Date])`
  - **Month** = `TEXT([Order Date], "mmmm")`
- **Loaded the final merged table** into the **Data Model** for pivot table analysis.


---


## 📊 Data Analysis & Dashboard Insights

The analysis focused on four key business questions using Pivot Tables and Charts:

### A. **Trend of Total Sales by Coffee Type** (Column Chart)
- **Pivot Setup:**
  - Rows: `Year` (from Order Date)
  - Columns: `Coffee Type`
  - Values: `Sum of Total Sales`
- **Purpose:** Identifies yearly sales trends across different coffee types.

---

### B. **Top 10 Customers by Contribution** (Bar Chart)
- **Pivot Setup:**
  - Rows: `Customer Name`
  - Values: `Sum of Total Sales`
  - Sort: Descending
  - Filter: Top 10 by Sum of Total Sales
- **KPI:** Top 10 customers contributed **8%** of total sales.
- **Purpose:** Highlights key customers driving revenue.

---

### C. **Total Sales by Country** (Pie Chart)
- **Pivot Setup:**
  - Rows: `Country`
  - Values: `Sum of Total Sales`
- **Purpose:** Shows sales distribution across different regions.

---

### D. **Total Quantity Ordered by Coffee Type** (Pie Chart)
- **Pivot Setup:**
  - Rows: `Coffee Type`
  - Values: `Sum of Quantity`
- **Purpose:** Displays the demand volume for each coffee type.

---


  ## 📊 Dashboard Preview
Here is the interactive Coffee Shop Sales Analysis Dashboard created in Excel:
- <a href="https://github.com/JaySpesh/Coffee-Data-Analysis/blob/main/Coffee%20Sales%20Dashboard.png">View Dashboard</a>


---

### 👤 Author
**Dare Joseph**  
- Email: dareyjoseph25@gmail.com  
- LinkedIn: *(www.linkedin.com/in/joseph-boluwatife-dare-075353336)* 



