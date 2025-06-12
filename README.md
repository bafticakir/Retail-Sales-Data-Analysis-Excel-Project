# 📊 Retail Sales Data Analysis – Excel Project

This project demonstrates various Excel techniques and data analysis methods using retail and student performance datasets. It includes data cleaning, formula application, pivot tables, conditional formatting, and visualisations.

---

## 📁 Files and Sheets Included

- **`retail_sales_dataset - BAFTI.xlsx`**
  - `retail_sales_dataset` (Main sales data)
  - `Transactions` (Transaction-level sales)
  - `Task 2` (Student scores)
  - `Bar Chart` (Pivot analysis)

- **`Retail_Sales_by_County day 3 task 2 bafti cakir.xlsx`**
  - County-wise product sales and categorisation

---

## ✅ Tasks & Techniques Demonstrated

### 📌 Student Performance Analysis – `Task 2`

#### 🎯 Objectives:

1. **Apply filter & sorting** to show the best students in each subject.
2. **Average calculation** with:
   ```excel
   =AVERAGE(B2:D2)
   ```
3. **Find the highest score** using:
   ```excel
   =MAX(B2:D2)
   ```
4. **Sort students** by their average and highlight top performers.
5. **Use Conditional Formatting** to identify highest and lowest averages with colour scales.

#### 📷 Visual Elements:
- Colour-coded averages for easy comparison.
- Tasks listed directly in the sheet for clarity.

---

### 💳 Transaction Data – `Transactions`

#### 🛠 Techniques Used:

- Concatenating fields using:
  ```excel
  =CONCATENATE(B2, " ", C2)
  ```

- Clear labelling of transaction data for better readability.

---

### 📈 Pivot Table & Chart – `Bar Chart`

![Screenshot (448)](https://github.com/user-attachments/assets/131d9411-c820-41a9-bf73-52d28fb92240)

#### 📊 Insights Shown:

- Sum of **Total Sales** by:
  - Product Category (Beauty, Clothing, Electronics)
  - Gender (Male, Female)
  - Generation (Adult, Senior, Young Adult)

#### 💡 Filters & Structure:
- Pivot table filtered by `Gender`, `Product Category`, `Generation`
- Fields in use:
  - **Rows:** Gender, Product Category
  - **Columns:** Generation
  - **Values:** Sum of Total Sales

- Includes a bar chart for comparison across dimensions

---

### 🧮 Retail Sales by County – `Retail_Sales_by_County`

#### 🔍 Categorising Sales Volumes:

Used `SWITCH` formula for categorising sales as Low, Medium, or High:
```excel
=SWITCH(TRUE, C2 > 600, "High", C2 >= 300, "Medium", "Low")
```

#### 📊 Summary Table:

- Pivot table to show **Sum of Sales** by:
  - County
  - Product Type: Laptops, Printers, Smartphones

---

## 💡 Skills Demonstrated

- Basic & advanced Excel formulas (`AVERAGE`, `MAX`, `SWITCH`, `CONCATENATE`)
- Conditional Formatting
- Sorting and Filtering
- Pivot Tables and Pivot Charts
- Sales categorisation logic
- Gender and generation breakdown for analysis
- Data summarisation and dashboard creation


> Created 🔥 by **Bafti Cakir**
