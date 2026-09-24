# E-Commerce Sales & Customer Analytics Dashboard

An interactive Power BI dashboard designed to analyze e-commerce sales, profitability, customer behavior, product performance, payment methods, shipping operations, and order trends.

---

## Project Overview

This project transforms raw e-commerce transaction data into an interactive Business Intelligence dashboard using Power BI.

The dashboard provides a comprehensive view of:

- Sales performance
- Profitability
- Customer behavior
- Product performance
- Order status
- Payment methods
- Shipping operations
- Regional sales
- Business KPIs

---

## Business Objectives

- Monitor overall sales and profit performance
- Track sales and profit trends over time
- Identify high-performing products and categories
- Analyze customer segments and purchasing behavior
- Understand regional sales performance
- Analyze payment and shipping methods
- Monitor order status and operational performance
- Support data-driven business decisions

---

## Dataset

The project uses six related datasets:

| Dataset | Description |
|---|---|
| FactSales | Transaction-level sales and order data |
| DimCustomer | Customer information and segmentation |
| DimDate | Date, year, quarter and month information |
| DimProduct | Product, category, brand and pricing information |
| DimPayment | Payment method information |
| DimShipping | Shipping mode and delivery information |

---

## Data Model

The project follows a **Star Schema** data model.

### Fact Table

- FactSales

### Dimension Tables

- DimCustomer
- DimDate
- DimProduct
- DimPayment
- DimShipping

### Relationships

- DimCustomer → FactSales
- DimDate → FactSales
- DimProduct → FactSales
- DimPayment → FactSales
- DimShipping → FactSales

This model enables efficient filtering and analysis across different business dimensions.

---

## Dashboard Pages

### 1. Executive Overview

Provides a high-level summary of business performance.

**Key Metrics:**

- Total Sales
- Total Profit
- Profit Margin
- Total Orders
- Total Customers
- Average Order Value

**Visual Analysis:**

- Monthly Sales Trend
- Sales by State
- Sales by Category
- Sales by Payment Method
- Order Status Analysis

---

### 2. Sales Analytics

Focuses on revenue growth and profitability.

**Includes:**

- Monthly Sales Trend
- Quarterly Sales Performance
- Monthly Profit Trend
- Sales by State
- Sales by Order Status
- YoY Sales Growth

---

### 3. Product Analytics

Analyzes product and category performance.

**Includes:**

- Sales by Category
- Sales by Brand
- Sales by Sub-Category
- Product Price vs Profit

---

### 4. Customer Analytics

Analyzes customer demographics and purchasing behavior.

**Includes:**

- Customer Segment vs Profit
- Orders by State
- Average Order Value by Segment
- Customer Age vs Sales
- Orders by Gender

---

### 5. Operations & Payment

Analyzes operational and payment performance.

**Includes:**

- Orders by Payment Method
- Sales by Shipping Mode
- Order Status Analysis
- Average Delivery Days by Shipping Mode
- Sales by Order Status

---

### 6. Drill-through Detail

Provides transaction-level order details.

Users can drill through to individual orders and analyze:

- Order ID
- Order Date
- Customer
- Product
- Category
- Quantity
- Sales Amount
- Profit
- Order Status

---

## Key Performance Indicators

The dashboard includes DAX measures for:

- Total Sales
- Total Cost
- Total Profit
- Total Orders
- Total Customers
- Total Quantity
- Products Sold
- Profit Margin %
- Average Order Value
- Revenue Per Customer
- Orders Per Customer
- Average Selling Price
- YoY Sales Growth %
- Sales YTD
- Profit YTD
- Delivered Order %
- Cancellation Rate %
- Profit Per Order
- Loss Making Order %

---

## DAX & Analytics

Advanced DAX calculations are used for:

- Time intelligence
- Year-over-Year growth
- YTD analysis
- Profitability analysis
- Customer segmentation
- Product ranking
- Category ranking
- Dynamic calculations
- KPI analysis

---

## Tools & Technologies

- Power BI
- DAX
- Microsoft Excel / CSV
- Data Modeling
- Star Schema
- Data Visualization
- Business Intelligence

---

## Project Highlights

- Interactive Power BI dashboard
- Star schema data model
- Multiple analytical dashboard pages
- Advanced DAX measures
- Time intelligence analysis
- Drill-through functionality
- Interactive slicers and filters
- KPI-driven business analysis
- Product and customer analytics
- Operational and payment analysis
- Professional dark-themed dashboard design

---

## Project Structure

```text
ECommerce_PowerBI_Advanced_Project/
│
├── Data/
│   ├── FactSales.csv
│   ├── DimCustomer.csv
│   ├── DimDate.csv
│   ├── DimPayment.csv
│   ├── DimProduct.csv
│   └── DimShipping.csv
│
├── DAX/
│   └── Advanced_Measures.dax
│
├── Icons/
│   ├── sales.png
│   ├── profit.png
│   ├── profit_margin.png
│   ├── orders.png
│   ├── customers.png
│   └── aov.webp
│
├── PowerBI_Assets/
│   └── ECommerce_Executive_Dark_Theme.json
│
├── Ecommerce.pbix
├── image1.jpg
└── README.md

## Author

**Vaishnavi Jadhav**

Aspiring Data Analyst | Power BI | SQL | Python | Excel

### Connect with Me

- LinkedIn: [Vaishnavi Jadhav](https://www.linkedin.com/in/vaishnavi-jadhav-66b640275/)
- GitHub: [vaishnavi19-coder](https://github.com/vaishnavi19-coder)
