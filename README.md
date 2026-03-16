# E-Commerce Sales & Returns Analysis (Q4 2024)

## Project Overview

This project analyzes **Q4 2024 e-commerce transaction data (October–December)** to understand sales trends, customer behavior, and product return patterns.

The goal of this project was to **clean and validate the dataset, perform exploratory analysis, and generate business insights** that can help reduce return rates and improve operational efficiency.

All stages of the project — **data cleaning, validation, analysis, KPI calculation, and visualization — were completed using Google Sheets.**

---

## Tools Used

The entire analysis workflow was completed using:

* **Google Sheets** 
* Spreadsheet formulas
* Pivot tables
* Charts and visualizations

Tasks performed in Sheets (all the sheets are in the file itself) :

* Data cleaning
* Data validation
* Feature engineering
* KPI calculations
* Trend analysis
* Category and return analysis
* Data visualization

---

## Dataset Description

The dataset contains **item-level e-commerce transaction data** including:

* Order ID
* Order Date
* Customer ID
* Customer Type (New / Returning)
* Product Category
* Product Name
* Unit Price
* Quantity
* Discount Code & Percentage
* Payment Method
* Order Source (Website / Mobile App / Instagram Shop)
* Delivery Status
* Return Status
* Return Reason
* Refund Status

**Dataset Period:** Q4 2024 (Oct–Dec)

---

## Data Cleaning Process

All cleaning operations were performed in **Google Sheets using formulas and validation checks**.

Key steps included:

* Standardizing inconsistent categorical values (delivery status, customer type)
* Handling missing values using logical rules
* Flagging invalid numerical values such as negative quantities
* Verifying discount values and recalculating totals
* Maintaining **raw data separately from working data**
* Documenting issues and fixes in a **Cleaning_Log sheet**

---

## Data Validation

A **rule-based validation framework** was implemented to ensure dataset integrity.

Validation rules included:

* Order dates restricted to Q4 2024
* Delivered orders must have delivery dates
* Return logic must match refund status
* Return initiation and completion consistency

Records failing validation checks were flagged and excluded from certain analyses when necessary.

---

## Key Business Metrics

| Metric                        | Value        |
| ----------------------------- | ------------ |
| Total Orders                  | 346          |
| Total Units Sold              | 409          |
| Gross Merchandise Value (GMV) | ₹9,68,309    |
| Net Revenue                   | ₹8,56,965.95 |
| Average Order Value           | ₹2,476.78    |

Return rate was calculated **at the order level**.
Because the dataset contains **item-level transactions**, the observed return rate appears higher than typical industry benchmarks.

---

## Analysis Performed

### Sales Trend Analysis

* Order volume peaked in **October and December**, indicating strong festive demand.
* November showed a dip following the festival season.

### Weekly Demand Patterns

A noticeable spike in orders occurs during **late October (Diwali shopping period)**.

### Category Performance

Top categories by order volume:

1. Tops
2. Dresses
3. Outerwear

Accessories recorded **lower sales but also the lowest return rates**.

---

## Return Behavior Analysis

Categories with the highest return rates:

| Category    | Insight             |
| ----------- | ------------------- |
| Outerwear   | Highest return rate |
| Dresses     | High return rate    |
| Tops        | Above average       |
| Accessories | Lowest return rate  |

These categories contribute significantly to revenue, making return reduction operationally important.

---

## Return Reasons

Primary reasons for product returns:

| Reason             | Approx Share |
| ------------------ | ------------ |
| Size Issue         | ~37%         |
| Quality Defect     | ~18%         |
| Changed Mind       | ~16%         |
| Wrong Item         | ~15%         |
| Damaged in Transit | ~13%         |

Approximately **47% of returns are operationally controllable** through better product information, sizing guidance, and quality improvements.

---

## Key Insights

Important findings from the analysis:

* Sales spikes occur during festive promotional periods.
* Return rates increase **1–2 weeks after sales spikes**.
* Apparel categories show the highest return rates.
* **New customers return products more frequently than repeat customers.**
* Instagram Shop shows higher return risk compared to other channels.
* **Cash-on-Delivery orders have higher return and RTO exposure than prepaid orders.**

---

## Business Recommendations

### Improve Size & Fit Guidance

Enhance size charts and fit recommendations for apparel categories.

### Strengthen Quality Control

Focus quality improvements on high-return categories such as **Outerwear and Dresses**.

### Manage Promotional Discounts

Apply discount guardrails during festive sales for categories with historically high return rates.

### Encourage Prepaid Orders

Provide incentives such as loyalty points or faster refunds for prepaid transactions.

### Monitor High-Risk Segments

Track return patterns for **new customers and social commerce channels**.


---

## Skills Demonstrated

* Data Cleaning
* Spreadsheet Analytics
* Data Validation
* Exploratory Data Analysis
* Customer Behavior Analysis
* Return Rate Analysis
* Business Insights & Recommendations
* Data Visualization

---

## Author

**Aashi Vidyarthi**
Data Analyst | Python | SQL | Data Analytics
