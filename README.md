# 📊 Shopify Stock Analysis using Power BI

## 📌 Project Overview

This project presents an interactive **Power BI dashboard for Shopify (SHOP) stock market analysis**.

The project analyzes historical Shopify stock market data to understand stock price movements, trading volume, and time-based trends.

The complete workflow includes:

* Data loading
* Data inspection
* Data cleaning
* Data transformation
* Date dimension creation
* Data modeling
* DAX calculations
* Time-based analysis
* Interactive data visualization
* Power BI dashboard development

The main objective is to convert raw Shopify stock data into meaningful and interactive visual insights using **Microsoft Power BI**.

---

## 🎯 Objectives

* Analyze historical Shopify stock data.
* Understand stock price movements over time.
* Analyze opening, closing, high, and low prices.
* Examine adjusted closing prices.
* Analyze trading volume.
* Identify monthly, quarterly, and yearly trends.
* Create a dedicated Date Dimension for time-based analysis.
* Apply DAX calculations for time intelligence.
* Build an interactive Power BI dashboard.
* Present stock market information in a clear and understandable format.

---

## 📂 Dataset

The project uses historical stock market data for **Shopify (SHOP)**.

The dataset contains daily stock market information.

### Dataset Columns

| Column    | Description                        |
| --------- | ---------------------------------- |
| Date      | Date of stock trading              |
| Open      | Opening stock price                |
| High      | Highest stock price during the day |
| Low       | Lowest stock price during the day  |
| Close     | Closing stock price                |
| Adj Close | Adjusted closing price             |
| Volume    | Number of shares traded            |

---

## 🛠️ Tools & Technologies

* **Microsoft Power BI**
* **Power Query**
* **DAX**
* **Data Modeling**
* **Data Visualization**
* **Stock Market Data Analysis**

---

## 🔄 Complete Project Workflow

```text
Shopify Stock Dataset
        ↓
Data Import
        ↓
Data Inspection
        ↓
Data Cleaning
        ↓
Data Transformation
        ↓
Create Dim_Date Table
        ↓
Create Calendar Columns
        ↓
Create Relationships
        ↓
Create DAX Measures
        ↓
Build Visualizations
        ↓
Add Filters & Slicers
        ↓
Interactive Power BI Dashboard
```

---

## 🗓️ Date Dimension

A dedicated **Dim_Date** table was created to support time-based analysis.

The Date Dimension contains:

* Date
* Day
* Month
* Month Number
* Month Name
* Quarter
* Year
* Year-Month

The Date Dimension is connected to the stock data using the **Date** column.

This enables analysis at different time levels such as:

* Daily
* Monthly
* Quarterly
* Yearly

---

## 📐 DAX Measures

DAX measures were created to calculate important stock market metrics.

Example measures include:

```DAX
Total Volume =
SUM(SHOP[Volume])
```

```DAX
Average Close =
AVERAGE(SHOP[Close])
```

```DAX
Highest Price =
MAX(SHOP[High])
```

```DAX
Lowest Price =
MIN(SHOP[Low])
```

```DAX
Average Open =
AVERAGE(SHOP[Open])
```

```DAX
Average Adjusted Close =
AVERAGE(SHOP[Adj Close])
```

These measures help provide summarized insights through Power BI visuals.

---

## 📊 Dashboard Visualizations

The Power BI dashboard includes interactive visualizations such as:

* **KPI Cards** for key
