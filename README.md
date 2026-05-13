# powerbi-ecommerce-dashboard
Interactive Ecommerce Sales Dashboard built using Power Bi.

# 🛒 E-Commerce Sales Dashboard — Power BI

A comprehensive, single-page **Power BI dashboard** built to analyze and monitor key e-commerce metrics including revenue trends, product performance, customer segmentation, and geographic sales distribution.

---

## 📊 Dashboard Preview

> Open `E-Commerce_Sales.pbix` in **Power BI Desktop** to interact with the full dashboard.

---

## 🎯 Key Metrics (KPI Cards)

| Metric | Description |
|---|---|
| **Total Revenue** | Sum of all revenue generated across the dataset |
| **Total Orders** | Count of all orders placed |
| **Total Customers** | Count of unique customers |
| **Avg. Order Value (AOV)** | Average revenue per order |

---

## 📈 Visuals & Charts

### 1. 📉 Monthly Revenue Trend *(Line Chart)*
Tracks how revenue evolves month by month to identify seasonal patterns and growth trends.

### 2. 🔵 Quantity vs Revenue *(Scatter Chart)*
Plots individual products by quantity sold against revenue to identify high-performing SKUs.

### 3. 🌍 Top 10 Countries by Revenue *(Clustered Bar Chart)*
Highlights the top 10 countries contributing the most to overall revenue.

### 4. 📦 Revenue by Products *(Clustered Bar Chart)*
Ranks products by the revenue they generate to surface bestsellers.

### 5. 🍩 Customer Segmentation *(Donut Chart)*
Breaks down customers into segments (e.g., new vs returning) based on purchase behavior.

---

## 🎛️ Interactive Filters (Slicers)

| Slicer | Field | Purpose |
|---|---|---|
| **Month** | Month Name | Filter data by month |
| **Year** | Year | Filter data by year |
| **Country** | Country | Filter data by geography |

---

### Key Columns Used

| Column | Description |
|---|---|
| `InvoiceNo` | Unique invoice/order identifier |
| `Description` | Product name |
| `Quantity` | Number of units purchased |
| `UnitPrice` | Price per unit |
| `CustomerID` | Unique customer identifier |
| `Country` | Country of the customer |
| `Total_Sales` | Calculated column: `Quantity × UnitPrice` |
| `Month_Name` | Extracted from invoice date |
| `Year` | Extracted from invoice date |
| `customer type` | Customer segmentation label |

---

### Cleaning Steps Performed

- Removed null values
- Corrected data types
- Extracted Year, Month, and Day from date column
- Created Total Sales column
- Removed duplicate records
- Handled missing product descriptions
- Prepared data model for analysis

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| **Power BI Desktop** | Report design & data modeling |
| **DAX** | Custom measures & calculated columns |
| **Power Query (M)** | Data transformation & cleaning |

---

## 💡 Insights You Can Derive

- Which months drive peak revenue — plan inventory and marketing accordingly
- Which countries are top revenue contributors for geo-targeted strategy
- Which products generate the most sales vs. volume
- Customer segmentation split to understand loyalty and acquisition trends
- Month-over-month revenue growth rate

---

## Files Included

| File Name | Description |
|---|---|
| Ecommerce Dashboard.pbix | Power BI dashboard project |
| cleaned_ecommerce_sample.csv | Cleaned sample dataset |
| dashboard-preview.png | Dashboard screenshot |
| README.md | Project documentation |

## 📌 Notes

- The `.pbix` file contains both the **data model** and **report layout** — no external database connection is required.
- The dashboard uses the **Tidal** built-in theme for visual styling.
- All slicers are cross-filtered — selecting one filter affects all visuals on the page.
- Due to GitHub file size limitations, a sample cleaned dataset has been uploaded instead of the complete dataset.

---

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Fork the repo
- Add new pages or visuals
- Improve DAX measures
- Submit a pull request
  
---

## 👤 Author

**Tushant Chaudhari**
- GitHub: https://github.com/tushantac2003-prog
- LinkedIn: https://www.linkedin.com/in/tushant-chaudhari-a62b10298

---

> ⭐ If you found this useful, please give the repo a star!
