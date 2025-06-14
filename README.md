# 🧩 Task 8: Simple Sales Dashboard Design

## 📌 Objective
Create a basic interactive dashboard in **Power BI** to visualize sales performance by product, region, and time.

---

## 📁 Dataset
**File**: `Sample_Superstore_Sales.csv`  
**Columns Used**:
- Order Date
- Region
- Category
- Sales
- Profit

A new column `MonthYear` was created using DAX to format Order Date:

```DAX
MonthYear = FORMAT('Sample_Superstore_Sales'[Order Date], "MMM-YYYY")
