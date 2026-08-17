# 📊 Zepto Sales Dashboard

An interactive **Zepto Sales Dashboard built in Microsoft Excel** to
analyze sales performance, customer behavior, order trends, product
activity, and payment methods.

This project demonstrates a complete data analytics workflow:

**Raw Data → Data Cleaning → Data Validation → Analysis → Visualization
→ Business Insights**

------------------------------------------------------------------------

## 🚀 Project Overview

The Zepto Sales Dashboard converts a raw sales dataset into an
interactive and easy-to-understand business dashboard.

The dataset contains **1,500 orders, 300 customers, 200 products, and 22
attributes** covering order, customer, product, sales, payment, and
delivery information.

### 🎯 Objectives

-   Analyze overall sales performance
-   Track order and customer KPIs
-   Identify sales trends over time
-   Analyze payment method preferences
-   Understand customer-type contribution
-   Monitor daily sales volume
-   Identify top-performing orders
-   Enable city-wise filtering for interactive analysis

------------------------------------------------------------------------

## 📁 Dataset Information

  Metric                           Value
  ------------------------- ------------
  Total Orders                     1,500
  Total Sales                 563,992.25
  Total Quantity Sold              4,207
  Total Customers                    300
  Total Products                     200
  Average Sales per Order         375.99
  Dataset Columns                     22
  Cities                               4
  Payment Methods                      7
  Customer Types                       3

### Dataset Columns

The raw dataset includes:

`Order_ID`, `Order_Date`, `days`, `month`, `Customer_Name`,
`Customer_Type`, `Customer_Segment`, `City`, `Payment_Method`, `SKU`,
`Product_Name`, `Category`, `Qty`, `Price`, `Discount`, `Subtotal`,
`Tax`, `Delivery_Fee`, `Surge_Fee`, `Sales`, `Delivery_Status`, and
`Delivery_Time`.

------------------------------------------------------------------------

## 🧹 Data Cleaning & Preparation

Before creating the dashboard, the dataset was reviewed and prepared for
analysis.

### Data quality checks performed

-   Checked all **1,500 records** for missing values
-   Verified that there were **no blank values** in the main dataset
-   Checked for duplicate records
-   Verified that all **Order_IDs are unique**
-   Reviewed date, month, and day fields for time-based analysis
-   Validated numeric fields such as **Qty, Price, Discount, Subtotal,
    Tax, Delivery Fee, Surge Fee, and Sales**
-   Reviewed categorical fields such as **City, Customer Type, Payment
    Method, and Delivery Status**
-   Identified and reviewed the `N/A` city category
-   Verified product and SKU consistency
-   Prepared the data for Pivot Tables, KPI calculations, and charts

------------------------------------------------------------------------

## 📈 Dashboard Features

### KPI Cards

The dashboard displays:

-   💰 **Total Sales:** 563,992.25
-   🛒 **Total Orders:** 1,500
-   📦 **Total Products:** 200
-   📊 **Average Sales:** 375.99
-   👥 **Total Customers:** 300

### Visualizations

#### 1. Top 10 Orders

A horizontal bar chart showing the highest-value orders.

#### 2. Sales Trend Over Month

A line chart used to understand how sales changed across the available
months.

#### 3. Total Orders by Payment Method

A doughnut chart comparing orders made through:

-   Card
-   COD
-   GPay
-   Netbanking
-   PhonePe
-   UPI
-   Wallet

#### 4. Customer Type Contribution

A pie chart showing the contribution of:

-   Bulk Customers
-   New Customers
-   Returning Customers

#### 5. Daily Sales Volume

An area chart showing sales volume across the days of the month.

#### 6. City Filter

An interactive city filter is available for:

-   Bangalore
-   Delhi
-   Mumbai
-   N/A

------------------------------------------------------------------------

## 🛠️ Tools & Technologies

-   **Microsoft Excel**
-   Pivot Tables
-   Pivot Charts
-   Excel Formulas
-   Data Cleaning
-   Data Validation
-   Data Visualization
-   Dashboard Design
-   Business Analysis

------------------------------------------------------------------------

## 🔍 Key Insights

The dashboard can be used to answer questions such as:

1.  What is the overall sales performance?
2.  Which orders contribute the most to sales?
3.  How do sales change month over month?
4.  Which payment method is used most frequently?
5.  Which customer type contributes the most quantity?
6.  How does daily sales volume fluctuate?
7.  How does sales performance vary by city?
8.  What are the major delivery statuses?
9.  Which products and categories should be monitored for performance?
10. How can customer and payment trends support business decisions?

------------------------------------------------------------------------

## 📂 Repository Structure

``` text
zepto-sales-dashboard/
│
├── README.md
├── Zepto_Sales_Dashboard.xlsx
│
├── data/
│   └── zepto_sales_raw.xlsx
│
└── images/
    └── dashboard_screenshot.png
```

------------------------------------------------------------------------

## ▶️ How to Use

1.  Download or clone this repository.
2.  Open `Zepto_Sales_Dashboard.xlsx` in Microsoft Excel.
3.  Use the city filter to explore different locations.
4.  Interact with the dashboard charts and Pivot Tables.
5.  Review the KPI cards and trends to understand sales performance.

------------------------------------------------------------------------

## 💡 Project Learning

This project helped strengthen practical skills in:

-   Data cleaning and validation
-   Excel-based data analysis
-   KPI creation
-   Pivot Tables and Pivot Charts
-   Data visualization
-   Dashboard design
-   Business-oriented analytical thinking

------------------------------------------------------------------------

## 🔮 Future Improvements

Possible future enhancements include:

-   Adding more advanced KPI cards
-   Adding profit and margin analysis
-   Adding product/category-level drill-downs
-   Creating year-over-year comparisons
-   Building the dashboard in **Power BI**
-   Adding automated data refresh
-   Adding predictive sales analysis

------------------------------------------------------------------------

## 👨‍💻 Author

**Nirmal Pawar**

Aspiring **Data Analyst** \| Excel \| SQL \| Python \| Data
Visualization \| Machine Learning

------------------------------------------------------------------------

⭐ If you find this project useful, consider giving the repository a
**star**!
