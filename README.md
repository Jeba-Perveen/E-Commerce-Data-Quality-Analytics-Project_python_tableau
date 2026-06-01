# From Raw Data to Reliable Insights: E-Commerce Data Quality & Analytics Project

## Project Overview
Data-driven organizations rely on accurate and reliable data for business reporting and decision-making. However, poor data quality can lead to misleading insights, inaccurate KPIs, and incorrect strategic decisions.

This project demonstrates an end-to-end data analytics workflow by transforming a messy e-commerce dataset into a business-ready dataset using Python and Pandas. The project highlights how data quality issues impact business reporting by comparing dashboards built before and after data cleaning.

---

## Business Problem
The raw e-commerce dataset contained multiple data quality issues that negatively affected reporting accuracy:

* Duplicate transaction records
* Missing values
* Inconsistent categorical values
* Invalid numerical values
* Text formatting inconsistencies
* Customer data inconsistencies

These issues resulted in:
* Inflated revenue reporting
* Incorrect order counts
* Misleading customer segmentation
* Inaccurate product and regional analysis

The objective was to identify, clean, validate, and transform the dataset into a reliable source for business intelligence reporting.

---

## Tools & Technologies

### Data Cleaning & Processing

* Python
* Pandas
* Jupyter Notebook

### Data Visualization

* Tableau Public

---

## Project Structure

```text
Ecommerce-Data-Quality-Analytics-Project/
│
├── data/
│   ├── raw_ecommerce_dataset.csv
│   └── cleaned_ecommerce_dataset.csv
│
├── dashboards/
│   ├── Raw_Data_Quality_Assessment_Dashboard.twbx
│   └── Business_Ready_Performance_Dashboard.twbx
│
├── images/
│   ├── raw_dashboard.png
│   └── cleaned_dashboard.png
│
├── notebook/
│   └── ecommerce_data_cleaning.ipynb
│
├── reports/
│   └── project_report.pdf
│
└── README.md
```

---

##  Data Quality Assessment

The following issues were identified during the initial audit:

| Data Quality Issue       | Impact                                      |
| ------------------------ | ------------------------------------------- |
| Duplicate Records        | Inflated revenue and order counts           |
| Missing Values           | Incomplete customer and product information |
| Inconsistent Categories  | Fragmented reporting                        |
| Gender Inconsistencies   | Incorrect customer segmentation             |
| Invalid Numerical Values | Distorted KPI calculations                  |
| Text Formatting Issues   | Duplicate business entities                 |

---

## Data Cleaning Process

The dataset was cleaned using a structured data quality framework:

### Data Audit
* Dataset profiling
* Missing value analysis
* Duplicate analysis
* Data type validation

### Data Cleaning

* Removed duplicate records
* Standardized categorical values
* Corrected text inconsistencies
* Handled missing values
* Removed invalid records
* Standardized customer attributes

### Validation

* Rechecked duplicates
* Revalidated null values
* Verified KPI calculations
* Confirmed business reporting consistency

---

## Dashboard Comparison

### Dashboard 1: Raw Data Quality Assessment Dashboard

This dashboard was built using the raw dataset before any cleaning activities.

Key Purpose:

* Demonstrate the impact of poor data quality
* Identify misleading KPIs
* Highlight reporting inconsistencies

### Dashboard 2: Business Ready Performance Dashboard

This dashboard was built using the cleaned dataset.

Key Purpose:

* Deliver accurate business reporting
* Improve KPI reliability
* Support data-driven decision making

---

##  Business Impact of Data Cleaning

### Revenue Accuracy

| Metric        | Before Cleaning | After Cleaning |
| ------------- | --------------- | -------------- |
| Total Revenue | ₹1,980.75M      | ₹1,925.17M     |

Revenue decreased after removing duplicate and invalid records, resulting in more accurate financial reporting.

---

### Order Count Accuracy

| Metric       | Before Cleaning | After Cleaning |
| ------------ | --------------- | -------------- |
| Total Orders | 230.00K         | 215.05K        |

Approximately 14.95K records were removed during the cleaning process, improving reporting reliability.

---

### Customer Segmentation Improvement

Before Cleaning:

* Male
* male
* M
* Female
* female
* F

After Cleaning:

* Male
* Female

This improved customer analytics and segmentation consistency.

---

### Product Category Standardization

Product categories were standardized to eliminate fragmented reporting and improve category-level performance analysis.

---

## Key Business Insights

### Revenue Performance

* Home and Electronics categories generated the highest revenue.
* Fashion remained a strong contributor to overall sales.

### Customer Insights

* Revenue distribution across genders was nearly balanced.
* Customer satisfaction scores remained stable after cleaning.

### Operational Insights

* Cancellation and Return Rates were approximately 20%.
* Order status distribution remained consistent after validation.

### Payment Analysis

* Credit Card and Wallet transactions generated the highest revenue contribution.

### Product Performance

* Running Shoes and Wireless Mouse emerged as top-selling products by quantity.

---


## Skills Demonstrated

* Data Cleaning
* Data Validation
* Data Quality Assessment
* Exploratory Data Analysis
* KPI Development
* Tableau Dashboard Development
* Business Intelligence Reporting
* Data Storytelling
* Pandas Data Manipulation
* Business Impact Analysis

---

## Project Outcome

This project demonstrates how poor data quality can significantly impact business reporting and decision-making. By applying systematic data cleaning and validation techniques, the dataset was transformed into a reliable source of business insights.

The comparison between raw and cleaned dashboards highlights the importance of data quality in modern analytics workflows and showcases an end-to-end data analyst skill set from data preparation to business reporting.

---

### Author

**Jeba Perveen**
