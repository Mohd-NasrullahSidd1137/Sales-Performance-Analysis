# 📊 Sales Performance Analysis Dashboard

An interactive **Sales Performance Analysis Dashboard** built using **Microsoft Power BI** to analyze sales trends, product performance, regional sales, and profitability.

The project helps understand business performance through interactive visualizations, KPIs, and filters.

## 📸 Dashboard Preview

### Page 1: Sales Overview
![Page 1 Sales Performance](Dashboard%20Image/Page1%20Sales%20Performance.PNG)

### Page 2: Regional Analysis
![Page 2 Regional Analysis](Dashboard%20Image/page2%20Regional%20analysis.PNG)
## 🎯 Project Objectives

- Analyze monthly revenue trends.
- Identify top-performing products and categories.
- Compare sales performance across regions.
- Evaluate sales channel performance.
- Analyze salesperson performance.
- Track revenue, profit, orders, average order value, and profit margin.
- Identify strong and weak areas of sales performance.

## 🛠️ Tools & Technologies

- **Microsoft Power BI** — Interactive dashboards and visualizations
- **Microsoft Excel** — Dataset management and data cleaning
- **DAX** — Calculated measures and KPIs
- **Power Query** — Data transformation

## 📈 Dashboard Features

### Page 1: Sales Overview

**Key Performance Indicators (KPIs)**
- Total Revenue
- Total Profit
- Total Orders
- Average Order Value

**Visualizations**
- Monthly Revenue Trend — Line Chart
- Top 10 Products by Revenue — Bar Chart
- Revenue by Category — Column Chart

**Interactive Filters**
- Year
- Region
- Category

### Page 2: Regional Analysis

**Key Performance Indicators (KPIs)**
- Total Revenue
- Total Profit
- Profit Margin

**Visualizations**
- Revenue by Region — Column Chart
- Profit by Region — Bar Chart
- Revenue by Sales Channel — Donut Chart
- Top 5 Salespersons by Revenue — Bar Chart

**Interactive Filters**
- Year
- Region
- Sales Channel

## 📂 Project Structure

```text
Sales-Performance-Analysis/
│
├── images/
│   ├── sales-overview.png
│   └── regional-analysis.png
│
├── Sales_Performance_Dashboard.pbix
├── Sales_Performance_Dataset.xlsx
└── README.md
```

## 📊 Dataset Information

The project uses a sales dataset containing order-level information, including:

- Order ID and Order Date
- Customer ID
- Product and Category
- Region and City
- Salesperson
- Sales Channel
- Quantity and Unit Price
- Discount and Revenue
- Cost and Profit
- Order Status

The dataset is used for analyzing sales performance and building interactive reports.

## 🧮 Key DAX Measures

**Total Revenue**
```DAX
Total Revenue =
SUM(Sales_Raw[Revenue])
```

**Total Profit**
```DAX
Total Profit =
SUM(Sales_Raw[Profit])
```

**Total Orders**
```DAX
Total Orders =
DISTINCTCOUNT(Sales_Raw[Order_ID])
```

**Average Order Value**
```DAX
Average Order Value =
DIVIDE([Total Revenue], [Total Orders], 0)
```

**Profit Margin**
```DAX
Profit Margin =
DIVIDE([Total Profit], [Total Revenue], 0)
```

## 💡 Business Insights

The dashboard is designed to help users:

- Monitor revenue and profit trends over time.
- Discover products and categories contributing to sales.
- Compare regional performance.
- Understand the contribution of different sales channels.
- Identify high-performing salespersons.
- Evaluate profitability using key metrics.

## 🚀 How to Use

1. Clone or download this repository.
2. Open `Sales_Performance_Dashboard.pbix` using Microsoft Power BI Desktop.
3. If prompted, update the dataset source path.
4. Refresh the data.
5. Explore the dashboard using the interactive slicers and visuals.

## 👨‍💻 Author

**Mohd Nasrullah Siddiqui**

⭐ If you find this project useful, consider giving it a star!
