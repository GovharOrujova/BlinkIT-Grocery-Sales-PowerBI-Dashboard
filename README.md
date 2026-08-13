# BlinkIT-Grocery-Sales-PowerBI-Dashboard
Interactive Power BI dashboard analyzing BlinkIT grocery sales, item performance, outlet characteristics, ratings, and sales trends.

# 🛒 BlinkIT Grocery Sales Analysis — Power BI Dashboard


## 📌 Project Overview

The dataset contains **8,523 records and 12 columns** related to grocery items and BlinkIT outlets.

### Dataset Fields

* Item Fat Content
* Item Identifier
* Item Type
* Outlet Establishment Year
* Outlet Identifier
* Outlet Location Type
* Outlet Size
* Outlet Type
* Item Visibility
* Item Weight
* Sales
* Rating

The dashboard provides a single-page interactive overview combining **KPI cards, bar charts, donut charts, a line chart, funnel analysis, matrix analysis, and slicers**.

---

## 🔍 Analysis Key

The dashboard was designed to answer questions such as:

* What is the total sales performance of BlinkIT outlets?
* What is the average sales value per item?
* What is the average customer rating?
* Which item types generate the highest sales?
* How are sales distributed between Low Fat and Regular products?
* How does fat content performance differ across outlet locations?
* Which outlet sizes contribute the most sales?
* Which outlet location tiers generate the highest revenue?
* How does outlet establishment year relate to sales performance?
* How do different outlet types compare in terms of sales, item count, average sales, and rating?
* How do dashboard results change when filtering by outlet location, outlet size, or item type?

---

## 🗝 Key Concepts Used

### Data Cleaning & Transformation

The raw dataset required preparation before visualization.

Examples include:

* Standardizing inconsistent **Item Fat Content** values such as:

  * `LF`
  * `low fat`
  * `Low Fat`
  * `reg`
  * `Regular`
* Handling missing values in **Item Weight**
* Checking data types for numerical and categorical columns
* Preparing sales and rating fields for aggregation

### Power BI Data Modeling

The cleaned dataset was loaded into Power BI and structured for interactive analysis.

### DAX Measures

Custom measures were used to calculate important business KPIs, including:

* **Total Sales**
* **Average Sales**
* **Number of Items**
* **Average Rating**

### KPI Analysis

Card visuals provide a quick overview of the most important business metrics.

### Category Analysis

Product performance is analyzed across different **Item Types** and **Fat Content** categories.

### Outlet Analysis

Sales performance is compared using:

* Outlet Type
* Outlet Location Type
* Outlet Size
* Outlet Establishment Year

### Interactive Filtering

Slicers allow users to dynamically filter the dashboard by:

* Outlet Location Type
* Outlet Size
* Item Type

### Data Visualization

Multiple Power BI visuals were used to communicate insights clearly:

* KPI Cards
* Bar Charts
* Clustered Bar Charts
* Donut Charts
* Line Chart
* Funnel Chart
* Matrix
* Slicers

---

## 📊 Outputs

### KPI Cards

The dashboard displays four main KPIs:

**💰 Total Sales**

Shows the overall revenue generated from all grocery items.

**📈 Average Sales**

Shows the average sales value across all records.

**📦 Number of Items**

Displays the total number of item records analyzed.

**⭐ Average Rating**

Shows the overall average rating across the dataset.

---

### 🍩 Fat Content Analysis

A donut chart shows the contribution of different **Item Fat Content** categories to total sales.

This helps compare sales performance between:

* Low Fat products
* Regular products

---

### 📍 Fat Content by Outlet

A clustered bar chart compares total sales by:

* Outlet Location Type
* Item Fat Content

This visual helps identify whether product fat-content preferences differ between outlet locations.

---

### 🥫 Item Type Analysis

A bar chart compares **Total Sales by Item Type**.

It makes it easy to identify the strongest and weakest performing grocery categories.

---

### 📅 Outlet Establishment Analysis

A line chart analyzes **Total Sales by Outlet Establishment Year**.

This helps understand how outlets established in different years contribute to overall sales.

---

### 🏪 Outlet Size Analysis

A donut chart shows the distribution of total sales by:

* Small outlets
* Medium outlets
* High/Large outlets

---

### 🌍 Outlet Location Analysis

A funnel chart compares sales performance across different outlet location tiers:

* Tier 1
* Tier 2
* Tier 3

---

### 📋 Outlet Type Performance Matrix

The dashboard includes a detailed matrix comparing each **Outlet Type** using:

* Total Sales
* Number of Items
* Average Sales
* Average Rating

This allows multiple performance indicators to be compared in a single visual.

---

## 📊 Dataset Summary

| Metric                     |     Value |
| -------------------------- | --------: |
| Records                    |     8,523 |
| Columns                    |        12 |
| Total Sales                |    ~1.20M |
| Average Sales              |   ~140.99 |
| Average Rating             |     ~3.97 |
| Outlet Establishment Years | 2011–2022 |

---

## 🖼 Dashboard Preview

Add a screenshot of the finished Power BI dashboard to an `images` folder inside the repository.

```text
images/
└── blinkit-dashboard.png
```

Then display it in the README using:

```md
![BlinkIT Power BI Dashboard](images/blinkit-dashboard.png)
```

---

## 🚀 How to Run

### Requirements

* Microsoft Power BI Desktop
* Microsoft Excel

### Steps

1. Clone or download this repository.

```bash
git clone <your-repository-url>
```

2. Open the project folder.

3. Open:

```text
BlinkIT report.pbix
```

using **Microsoft Power BI Desktop**.

4. Make sure the dataset file is available:

```text
BlinkIT Grocery Data.xlsx
```

5. If Power BI cannot locate the Excel file, go to:

```text
Home
→ Transform Data
→ Data Source Settings
→ Change Source
```

6. Select `BlinkIT Grocery Data.xlsx` from your local computer.

7. Click **Refresh** to reload the dataset.

8. Use the dashboard slicers to interactively explore different outlet and item segments.

---

## 📁 Suggested Repository Structure

```text
blinkit-grocery-sales-powerbi-dashboard/
│
├── BlinkIT report.pbix
├── BlinkIT Grocery Data.xlsx
├── README.md
│
└── images/
    └── blinkit-dashboard.png
```

---

## 📝 Notes

* The project is created for **data analysis and portfolio purposes**.
* The dataset contains **8,523 grocery sales records**.
* Some values in `Item Fat Content` appear in different formats such as `LF`, `low fat`, `Low Fat`, `reg`, and `Regular`, so these values should be standardized during data cleaning.
* The `Item Weight` column contains missing values.
* The dataset includes outlets established between **2011 and 2022**.
* Power BI `.pbix` files cannot be previewed directly on GitHub, so including a dashboard screenshot in the repository is recommended.
* Dashboard results can dynamically change depending on the selected slicers and filters.

---

## 👤 About Me

📩 Contact: [govharorucova@outlook.com] 🌐 GitHub: [https://github.com/GovharOrujova]

[https://www.linkedin.com/in/govhar-orujova-64333b369/]

---

⭐ If you found this project useful, feel free to star the repository.
