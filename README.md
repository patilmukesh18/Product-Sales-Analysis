# 📊 Power BI Sales Analysis Dashboard

This project showcases an interactive **Sales Analysis Dashboard** built in **Power BI**, designed to help stakeholders monitor, analyze, and drive decisions based on key sales performance metrics.

---

## 🚀 Objective

To analyze and visualize sales data effectively using Power BI and deliver actionable business insights such as:
- Sales performance
- Profitability
- Discount impacts
- Regional analysis
- Product-level trends

---

## 📌 Dashboard Highlights

✅ **Total Orders, Sales, Profit Margin, Discount Value**  
✅ **Top 5 Products by Sales**  
✅ **Sales Trends Over Time (Yearly)**  
✅ **City-wise Sales Distribution**  
✅ **Interactive Filters by Date, Customer, and Promotion**  
✅ **Detailed Table View for Transactions and Discounts**

---

## 📷 Screenshots

### 🔍 Sales Analysis Dashboard
![Sales Dashboard](https://github.com/patilmukesh18/Product-Sales-Analysis/blob/main/Screenshot%202025-06-30%20114237.png)

---

## ✅ Requirements Covered

| # | Requirement Description | Implemented |
|--|---------------------------|-------------|
| 1 | Top/Bottom 5 products by Sales/Profit/Quantity Sold | ✅ |
| 2 | Sales trends over time (Yearly) | ✅ |
| 3 | Relationship between Sales & Profit | ❌ *(not shown in current version)* |
| 4 | Compare metrics between any two periods | ❌ *(can be added using bookmarks or slicers)* |
| 5 | Avg. discount per discount category | ✅ |
| 6 | Total number of orders | ✅ |
| 7 | Sales/Profit/Discount/Net Sales with filter options | ✅ |
| 8 | Sales by cities | ✅ |

---

## 📁 Files

- `SalesDashboard.pbix` - Power BI project file *(optional if you include the actual `.pbix`)*
- `ec29801d-8d1a-45a0-aa76-15aef0119d9e.png` - Dashboard Screenshot
- `README.md` - Project documentation

---

## 🛠 Tools Used

- Power BI Desktop
- DAX (Data Analysis Expressions)
- Excel/CSV for raw data import
- Custom visuals and slicers

---

## 📈 KPIs Calculated with DAX

- **Total Sales**: `SUM('Fact Table'[Total Sales])`
- **Total Net Sales**: `SUM('Fact Table'[Net Sales])`
- **Total Profit**: `SUM('Fact Table'[Profit])`
- **Profit Margin %**: `DIVIDE([Total Profit], [Total Net Sales], 0)`
- **Total Orders**: `COUNTROWS('Fact Table')`
- **Average Discount %**: `AVERAGE('Fact Table'[Discount Percentage])`

---

## 💡 Future Improvements

- Add scatter plot to show Sales vs Profit relationship.
- Enable time period comparison using dynamic slicers or bookmarks.
- Include Product Category-based analysis if applicable.

---

## 📬 Contact

Feel free to connect for feedback, suggestions, or collaborations:    
🔗 [https://www.linkedin.com/in/mukesh-patil/]

---

## 📜 License

This project is for educational/demo purposes only.
