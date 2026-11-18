# 💹 DAX Calculations – Financial Performance Analytics

## 🚀 Overview

DAX (Data Analysis Expressions) was used in Microsoft Power BI to calculate key financial performance indicators and develop an interactive financial dashboard.

The dashboard focuses on revenue, discounts, profitability, costs and sales volume.

## 📌 Financial KPI Measures

### 1. Total Sales

Calculates the total revenue generated from sales transactions.

```dax
Total Sales =
SUM(Finance_data[Sales])
```

**Dashboard Result:** 118.73M

### 2. Total Discount

Calculates the total discounts applied to sales transactions.

```dax
Total Discount =
SUM(Finance_data[Discounts])
```

**Dashboard Result:** 9.21M

### 3. Total Profit

Calculates the total profit generated from business operations.

```dax
Total profit =
SUM(Finance_data[Profit])
```

**Dashboard Result:** 16.89M

### 4. Total Unit Sold

Calculates the total number of units sold.

```dax
Total Unit Sold =
SUM(Finance_data[Units Sold])
```

**Dashboard Result:** 1.13M

### 5. Total COGS

Calculates the total Cost of Goods Sold.

```dax
Total COGS =
SUM(Finance_data[COGS])
```

**Dashboard Result:** 101.83M

### 6. Total Gross Sales

Calculates the total gross sales before discounts.

```dax
Total Gross Sales =
SUM(Finance_data[Gross Sales])
```

**Dashboard Result:** 127.93M

### 7. Profit Margin %

Calculates the percentage of sales revenue retained as profit.

```dax
Profit margin % =
DIVIDE(
    [Total profit],
    [Total Sales],
    0
)
```

**Dashboard Result:** 14.23%

## 📊 Business Applications of DAX

These measures support:

- Revenue monitoring.
- Profitability analysis.
- Discount evaluation.
- Cost analysis.
- Sales volume tracking.
- Financial performance reporting.
- Dynamic KPI analysis using interactive slicers.

## 🎛️ Interactive Analysis

The DAX measures support dynamic analysis through the dashboard filters:

- Country
- Product
- Segment
- Year
- Discount Band

## 🛠️ Tools Used

- Microsoft Power BI
- DAX
- Power Query
- Financial Sample Dataset

## 🎯 Conclusion

DAX calculations provide the foundation for financial KPI reporting and profitability analysis.

Combining DAX measures with Power BI visualizations helps transform financial transaction data into meaningful business performance indicators.
