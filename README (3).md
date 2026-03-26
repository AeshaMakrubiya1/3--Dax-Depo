# 🚀 DAX Depo – Advanced DAX Calculations in Power BI  

> **A complete backend-focused Power BI project showcasing advanced DAX concepts using a clean Star Schema and Matrix-only reporting.**

---

## 📌 Project Summary  

**DAX Depo** is an advanced Power BI project created to demonstrate how powerful insights can be generated **using DAX alone**, without relying on charts or fancy visuals.

This project was built based on a **Business Analyst Manager’s brief** to evaluate:
- Advanced DAX calculations
- Filter context behavior
- Time intelligence
- Iterator functions
- Clean data modeling practices

📊 **Only Matrix visuals are used** to display results.

---

## 🎯 Business Objective  

- Build a **robust Sales & Returns data model**
- Perform **advanced analytical calculations using DAX**
- Showcase **time-based insights and KPIs**
- Demonstrate **filter context control (ALL, FILTER, CALCULATE)**
- Organize all logic using a **Dedicated Measure Table**

---

## 🗂️ Dataset
📁 [DAX Depo Sample Dataset](./DAX_Depo_Sample_Datasets.xlsx)

## 🗂️ Dataset Information  

All required datasets are included in the folder below:


### 🧩 Tables Used

#### Fact Tables
- `Sales_Fact`
- `Returns_Fact`

#### Dimension Tables
- `Customer_Dim`
- `Product_Dim`
- `Date_Dim`
- `Region_Dim`

---

## 🧱 Data Model – Star Schema  

✔ One-to-Many relationships  
✔ Proper Primary & Foreign Keys  
✔ Filter flow from Dimensions → Facts  

### 🔗 Model View Screenshot
![Model View](./modelview.png)

---

## 🧮 Calculated Columns  

- **Profit** = SalesAmount − Cost  
- **ReturnFlag** = Returned / Not Returned  
- **Customer Full Name** = First Name + Last Name  

All calculated using **DAX Calculated Columns**.

---

## 📐 Measures Created  

### 🔢 Core Measures
- Total Sales  
- Total Cost  
- Total Profit  
- Return Rate (%)  
- Average Sale per Transaction  

### ⏳ Time Intelligence
- Sales YTD  
- Sales Last 3 Months  
- Running Total Sales  
- Year-over-Year Sales Growth  
- Month-over-Month Sales Difference  

### 🔁 Iterator Functions
- `SUMX()`
- `AVERAGEX()`

---

## 🎛️ Filter Context Demonstration  

The project clearly demonstrates filter behavior using:
- `ALL()`
- `FILTER()`
- `CALCULATE()`

This helps understand how context changes affect calculations inside a Matrix visual.

---

## 📊 Final Output (Matrix Only)  

📌 **Rows Used**
- Region  
- Year → Quarter → Month  
- Product Category  
- Customer Segment  

📌 **Values Displayed**
- Total Sales  
- Sales YTD  
- Sales Last 3 Months  
- Running Total  
- Total Profit  
- Total Cost  
- Average & Max Sales  

### 📈 Matrix Output Screenshot
![Matrix Output](./reportview.png)

---

## 🧠 DAX Functions Covered  

### ✔ Math & Aggregation
`SUM`, `AVERAGE`, `MAX`

### ✔ Counting
`COUNTX`, `DISTINCTCOUNT`

### ✔ Logical
`IF`, `AND`, `OR`, `SWITCH`

### ✔ Text
`CONCATENATE`, `UPPER`, `LEFT`

### ✔ Date & Time
`YEAR`, `MONTH`, `EOMONTH`  
`TOTALYTD`, `SAMEPERIODLASTYEAR`, `DATESINPERIOD`

### ✔ Relationships
`RELATED()`
---

## 🏆 Key Highlights  

✨ Advanced DAX-focused project  
✨ Clean Star Schema modeling  
✨ Matrix-only reporting discipline  
✨ Interview & portfolio ready  
✨ Strong demonstration of DAX thinking  

---

## 👨‍💻 Author  

**Krisha Anghan**  
📊 Data Analyst | Power BI | DAX  

> *“Strong models and clear DAX lead to confident decisions.”*

---

⭐ If you like this project, don’t forget to **star the repository**!





