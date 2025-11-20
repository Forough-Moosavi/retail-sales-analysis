# 📊 Retail Sales Analysis (Excel + Power BI Dashboard)

A complete **end-to-end Data Analytics project** using **Excel** and **Power BI**, based on a synthetic retail dataset of 300 sales transactions for an art supplies store in the UK.  
This project demonstrates skills in **data cleaning, EDA, data modeling, DAX, visualization, and dashboard design**.

---

## 📁 Project Structure

```
retail-sales-analysis/
│
├── data/
│   ├── raw/
│   │   └── retail_sales_300rows.csv
│   └── cleaned/
│
├── excel/
│   └── sales_analysis.xlsx
│
├── powerbi/
│   └── retail-sales-dashboard.pbix
│
├── screenshots/
│   ├── excel_city_pivot.png
│   ├── excel_month_pivot.png
│   ├── powerbi_dashboard.png
│
└── README.md
```

---

## 📌 Project Objectives

✔ Understand sales performance across products, cities, and months  
✔ Perform exploratory data analysis (EDA) in Excel  
✔ Build an interactive Power BI dashboard  
✔ Create business-ready insights for decision-making  

---

## 🧩 Dataset Description

Synthetic dataset (300 rows) representing sales from January to June 2025.

**Columns included:**

- Date  
- Product  
- Category  
- City  
- Quantity  
- UnitPrice  
- CostPerUnit  
- TotalSales *(calculated)*  
- Profit *(calculated)*  

---

## 📘 Step 1 — Excel Analysis (EDA)

### ✔ Added calculated fields:
- **TotalSales = Quantity × UnitPrice**  
- **Profit = TotalSales − (Quantity × CostPerUnit)**

### ✔ Built Pivot Tables:

#### 1️⃣ **Sales by City**  
📸 Located in: `screenshots/excel_city_pivot.png`

#### 2️⃣ **Monthly Sales Trend**  
📸 Located in: `screenshots/excel_month_pivot.png`

---

## 📊 Step 2 — Power BI Dashboard

Imported the dataset into Power BI and built an interactive dashboard.

### ✔ Created DAX Columns:

```DAX
TotalSales = retail_sales_300rows[Quantity] * retail_sales_300rows[UnitPrice]

Profit = retail_sales_300rows[TotalSales] - 
         (retail_sales_300rows[Quantity] * retail_sales_300rows[CostPerUnit])
```

---

## 📈 Dashboard Visuals

### 1️⃣ Monthly Sales Trend (Line Chart)  
Shows how sales evolved across months.

### 2️⃣ Total Sales per City (Bar Chart)  
Identifies top-performing cities.

### 3️⃣ Total Sales per Product (Column Chart)  
Reveals highest and lowest selling products.

### 4️⃣ Interactive Slicers:
- City  
- Product  
- Month  

📸 Screenshot: `screenshots/powerbi_dashboard.png`

---

## 💡 Key Insights

- **Southampton** had the highest total sales.  
- **Marker Pack** and **Watercolor Set** were the best-selling products.  
- Sales peaked in **March** and **May**.  
- Profit trends closely follow sales volume.  

---

## 🛠 Tools Used

- **Excel** (Pivot Tables, Formulas)  
- **Power BI Desktop** (DAX, Visuals)  
- **GitHub** (Project documentation)

---

## ✔ Conclusion

This project demonstrates real-world data analysis skills:

- Data cleaning  
- Exploratory analysis  
- DAX calculations  
- Dashboard creation  
- Project documentation  

It is suitable for Data Analyst job applications and technical interviews.

---

## 📬 Contact

**Forough Moosavi**  
Data Analyst — Southampton, UK  
GitHub: https://github.com/Forough-Moosavi
