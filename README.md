# 📊 Amazon Sales Report Analysis

## 📁 Dataset Information

* **File Name**: `Amazon Sale Report.csv`
* **Total Rows**: 128,976
* **Total Columns**: 21

### 📌 Key Columns:
- `Order ID`, `Date`, `Status`, `Fulfilment`, `Sales Channel`
- `Category`, `Size`, `Qty`, `Amount`
- `ship-city`, `ship-state`, `ship-country`

---

## ✅ Work Completed So Far

### 🔹 Step 1: File Loading
* Loaded the CSV file using `pandas` with correct encoding (`ISO-8859-1`).

### 🔹 Step 2: Initial Inspection
* Reviewed structure, data types, column names.
* Identified null values and redundant columns.

### 🔹 Step 3: Data Cleaning
* Dropped irrelevant columns (`index`, `New`, `PendingS`).
* Converted `Date` column to `datetime`.
* Dropped rows with nulls in important fields (`Date`, `Amount`, `ship-city`, `ship-state`).
* Renamed columns for clarity (e.g., `ship-city` → `City`, `ship-state` → `State`, `Qty` → `Quantity`).

### 🔹 Step 4: Verification
* Checked shape and sample records to ensure successful cleaning.

---

## 📈 Exploratory Data Analysis (EDA)

### 🔸 Sales Overview
* Analyzed sales performance using time-based data (in progress).

### 🔸 Product Analysis
* Identified top-selling **Sizes**.
* Evaluated **total quantity sold per product Category**.
* Visualized using horizontal bar charts.

### 🔸 Fulfillment Analysis
* Identified column related to fulfillment (`Fulfilment`) for future use.
* Fulfillment impact analysis queued.

### 🔸 Geographical Analysis
* Analyzed total sales by **Top 10 States** and **Top 10 Cities**.
* Visualized using bar charts (Seaborn).

---

## 🔮 Next Steps

- ⏳ **Sales Trend Analysis** over time (`Monthly`, `Quarterly`).
- 🚚 **Fulfillment Method Effectiveness** (comparison by delivery success or speed, if data available).
- 👥 **Customer Segmentation** based on spend and order frequency.
- 💡 **Business Insights & Recommendations**:
  - Optimize inventory based on product demand.
  - Target high-performing states/cities.
- 📊 **Dashboard or Report Generation** (PDF/Power BI/Excel).
- 📁 Final Submission: Visuals + Insights + GitHub Documentation.
