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
* Loaded the CSV file using `pandas` with proper encoding (`ISO-8859-1`).

### 🔹 Step 2: Initial Inspection
* Checked column names, data types, null values, and duplicates.
* Analyzed dataset structure for missing or irrelevant fields.

### 🔹 Step 3: Data Cleaning
* Dropped unnecessary columns like `index`, `New`, `PendingS`.
* Converted `Date` column to `datetime` format.
* Removed rows with missing values in critical fields (`Date`, `Amount`, `ship-city`, `ship-state`).
* Renamed key columns:
  - `ship-city` → `City`
  - `ship-state` → `State`
  - `Qty` → `Quantity`

### 🔹 Step 4: Exploratory Data Analysis (EDA)

#### 📅 Sales Overview
* Aggregated sales by **month** to identify trends.
* Visualized monthly sales using a line chart.

#### 🛍️ Product Analysis
* Identified top-selling **product categories**.
* Analyzed **sizes** and **quantities** sold.
* Created bar charts for category-wise performance.

#### 🚚 Fulfillment Analysis
* Compared total sales based on **Fulfilment Method** (Amazon vs Merchant).
* Highlighted which method generated more revenue.

#### 🌍 Geographical Analysis
* Identified **Top 10 States** and **Top 10 Cities** by total sales.
* Visualized regional performance using bar plots.

---

## 💡 Business Insights

* **April** was the peak month for sales.
* **T-shirts**, **Shirts**, and **Blazers** dominated sales by category.
* **Amazon-fulfilled orders** outperformed Merchant-fulfilled orders in volume.
* Sales are highest in metro cities: **Bengaluru**, **Hyderabad**, and **Mumbai**.
* Focused regional marketing and better fulfillment optimization could enhance revenue.

---

## 📈 Visualizations Used

- Monthly Sales Trend (Line Chart)
- Top Categories by Revenue (Bar Chart)
- Fulfilment Method Comparison (Bar Chart)
- Top 10 States and Cities by Sales (Bar Charts)

---

## 🛠️ Tools & Libraries Used

- **Python**: `pandas`, `matplotlib`, `seaborn`, `numpy`
- **Jupyter Notebook**
- **CSV File Handling**

---

## 🚧 Next Steps (Pending)

- 👥 **Customer Segmentation** (based on order frequency/spending) – *optional*
- 📊 **Dashboard or Report Generation** in PDF/Excel/Power BI
- 🧾 **Final Report Compilation** with visual insights
- 📁 **Documentation for GitHub**, final folder structuring
