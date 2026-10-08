# 🍕 Pizza Sales Analysis & Power BI Dashboard

Ek comprehensive end-to-end Data Analysis aur Business Intelligence project jisme pizza restaurant sales data ko analyze kiya gaya hai aur interactive **Power BI** dashboards banaye gaye hain business performance evaluate karne ke liye.

---

## 📌 Project Overview
Is project ka maqsad sales trends, customer order patterns, top & bottom performing pizzas, aur revenue distribution ko deeply analyze karna hai. Isse restaurant management ko data-driven decisions lene aur inventory/pricing optimize karne me madad milti hai.

---

## 📊 Key Business Metrics (KPIs)
* **Total Revenue:** $817.9K (Exact: $817,860.05)
* **Total Orders:** 21,350 (21K)
* **Total Pizzas Sold (Quantity):** 49,574
* **Average Order Value (AOV):** $38.31
* **Average Pizzas Per Order:** 2.32

---

## 🖥️ Dashboard Pages & Features

### 1. Dashboard 1: Executive Overview & Sales Trends
* **KPI Header Cards:** Total Orders, Total Quantity, Total Revenue, Average Order Value (AOV), aur Avg Pizzas per Order.
* **Day-of-Week & Slicer Filters:** Sun se Sat tak day filters, Pizza Category (Classic, Chicken, Supreme, Veggie), aur Pizza Size (S, M, L, XL, XXL).
* **Monthly Sales Trend (Line Chart):** Year ke monthly order fluctuations track karne ke liye.
* **Category Breakdown (Donut Chart & Bar Chart):**
  * Classic category highest sales volume lead karti hai (~14.9K pizzas).
  * Category revenue distribution (~$220K Classic, ~$208K Supreme, ~$196K Chicken, ~$194K Veggie).
* **Size Contribution (% Donut Chart):**
  * Large (L): ~45.89%
  * Medium (M): ~30.49%
  * Small (S): ~21.77%
  * XL & XXL: ~1.8%
* **Top 5 & Bottom 5 Pizzas by Revenue:** Best revenue-generating pizzas (jaise *The Thai Chicken Pizza*, *The Barbecue Chicken Pizza*) aur lowest revenue items (jaise *The Brie Carre Pizza*).

### 2. Dashboard 2: Best & Worst Sellers Breakdown
* **Top 5 Pizzas by Quantity & Orders:** Detailed volume analysis (Classic Deluxe Pizza aur BBQ Chicken leading).
* **Bottom 5 Pizzas by Quantity & Orders:** Underperforming items identify karke menu revamp karne ke insights.

### 3. Detailed Data Table View
* Order level granular data view (Order ID, Pizza ID, Date, Month, Weekday, Pizza Name, Size, Category, Quantity, Unit/Total Price).

---

## 🛠️ Tech Stack & Tools Used
* **Power BI Desktop:** Data Modeling, DAX Measures, Slicers, Bookmarks, and Visualizations.
* **DAX (Data Analysis Expressions):** KPIs calculation aur calculated columns ke liye.
* **Power Query:** Data cleaning, ETL pipeline, datatype correction, aur schema transformation.
* **Excel / CSV / SQL:** Raw sales data storage and extraction.

---

## 📁 Repository Structure
```text
├── dataset/
│   └── pizza_sales.csv            # Cleaned raw dataset
├── pbix/
│   └── Pizza_Sales_Report.pbix    # Complete Power BI Dashboard file
├── screenshots/
│   ├── dashboard_1_overview.png   # Page 1 Screenshot
│   ├── dashboard_2_deepdive.png   # Page 2 Screenshot
│   └── table_view.png             # Page 3 Screenshot
├── sql_queries/
│   └── pizza_sales_kpi.sql        # SQL verification queries
└── README.md                      # Project documentation
```
