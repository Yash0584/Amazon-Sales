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

## ✅ Work Completed

### 🔹 Step 1: File Loading
* Loaded the CSV file using `pandas` with proper encoding (`ISO-8859-1`).

### 🔹 Step 2: Initial Inspection
* Checked column names, data types, null values, and duplicates.
* Analyzed dataset structure and cleaned up irrelevant fields.

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
* Identified **April 2022** as the month with highest sales volume.

#### 🛍️ Product Analysis
* Top-selling categories by revenue:
  - **T-shirts**
  - **Shirts**
  - **Blazers**
* Quantity and size breakdown visualized.

#### 🚚 Fulfillment Analysis
* Compared Amazon-fulfilled vs merchant-fulfilled orders.
* Amazon-fulfilled orders generated more consistent revenue.

#### 🌍 Geographical Analysis
* Top 3 states by sales:
  - **Maharashtra**
  - **Karnataka**
  - **Telangana**
* Top-performing cities: **Bengaluru**, **Hyderabad**, **Mumbai**

#### 👥 Customer Segmentation (RFM Analysis)
* Used **RFM (Recency, Frequency, Monetary)** model to group customers based on behavior.
* Segmented users into:
  - **Loyal customers**: 2.37%
  - **Regular customers**: 97.63%
* Visualized customer tiers to identify retention and loyalty opportunities.

---

## 💡 Business Insights

* **April 2022** had the highest revenue peak — ideal for seasonal marketing.
* Focus marketing on **T-shirts, Shirts, and Blazers** — highest earning categories.
* Fulfillment by Amazon outperforms merchant handling — optimize for FBA.
* Strong revenue regions: **Maharashtra, Karnataka, Telangana**
* Customer base is mostly regular — loyalty programs can boost retention.

---

## 📈 Visualizations

- Monthly Sales Trend (Line Chart)
- Category-wise Sales Performance (Bar Chart)
- Fulfillment Comparison (Bar Chart)
- State-wise and City-wise Sales (Bar Charts)
- RFM Segmentation Bar Chart

---

## 🛠️ Tools & Libraries

- **Python**: `pandas`, `numpy`, `matplotlib`, `seaborn`, `plotly`
- **Jupyter Notebook**
- **Data Source**: Amazon Sales CSV Report

---

## 🚧 Next Steps

- 📊 Optional: Interactive **Dashboard** (Power BI or Plotly Dash)
- 📄 Export to **PDF/Excel Report** for stakeholders
- 📁 Finalize folder structure, **push to GitHub** with documentation
- 🧠 Consider applying **forecasting** for future sales predictions

---

