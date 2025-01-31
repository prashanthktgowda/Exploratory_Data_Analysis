# Exploratory Data Analysis (EDA) Report: Customer, Product, and Sales Insights

This repository contains the EDA report and key findings from the analysis of customer, product, and sales data. Below is a summary of insights and actionable takeaways derived from the analysis.

---

## Table of Contents
1. [Customer Analysis](#customer-analysis)
2. [Product Analysis](#product-analysis)
3. [Transactions Analysis](#transactions-analysis)
4. [Customer Purchasing Behavior](#customer-purchasing-behavior)
5. [Product Performance](#product-performance)
6. [Regional Sales Analysis](#regional-sales-analysis)
7. [Category-wise Sales](#category-wise-sales)
8. [Correlation Analysis](#correlation-analysis)
9. [Key Takeaways](#key-takeaways)

---

## Customer Analysis

### **Customers by Region**
- **Insight**: South America has the highest number of customers (60), followed by Asia (50), Europe (40), and North America (30).
- **Takeaway**: Focus marketing efforts on regions with fewer customers (e.g., North America) to expand the customer base.

### **Customer Sign-ups Over Time**
- **Insight**: Sign-ups are consistent monthly, with occasional spikes.
- **Takeaway**: Investigate months with higher sign-ups (e.g., marketing campaigns, promotions).

---

## Product Analysis

### **Products by Category**
- **Insight**: 
  - Electronics (25 products) > Books (20) > Clothing (15) > Home Decor (10).
- **Takeaway**: Expand the **Home Decor** category due to low product count.

### **Price Distribution**
- **Insight**: Most products are priced below $200; distribution is right-skewed.
- **Takeaway**: Introduce more mid-range products to cater to higher-spending customers.

---

## Transactions Analysis
- **Insight**: Transactions and sales show steady growth over time.
- **Takeaway**: Focus on increasing average order value to boost revenue.

---

## Customer Purchasing Behavior

### **Top Customers by Total Spending**
- **Insight**: A small group of high-value customers drives significant revenue.
- **Takeaway**: Implement loyalty programs to retain these customers.

### **Average Order Value (AOV)**
- **Insight**: Most customers have low AOV (below $200), with a few high-spending outliers.
- **Takeaway**: Use upselling or bundling strategies to increase AOV.

---

## Product Performance

### **Top Selling Products**
- **By Quantity**: ActiveWear Smartwatch, SoundWave Headphones, and HomeSense Desk Lamp.
- **By Revenue**: ActiveWear Smartwatch, SoundWave Headphones, and SoundWave Novel.
- **Takeaway**: Stock more high-revenue products (e.g., ActiveWear Smartwatch) and promote them.

---

## Regional Sales Analysis

### **Total Sales by Region**
- **Insight**: South America leads in sales, followed by Asia, Europe, and North America.
- **Takeaway**: Allocate resources to high-potential regions (South America and Asia).

### **Average Order Value by Region**
- **Insight**: North America has the highest AOV ($700) despite fewer customers.
- **Takeaway**: Target North American customers with premium products.

---

## Category-wise Sales

### **Sales by Product Category**
- **Revenue**: Electronics > Books > Clothing > Home Decor.
- **Quantity Sold**: Books > Electronics > Clothing > Home Decor.
- **Takeaway**: Increase prices for Books or bundle them with high-margin products.

---

## Correlation Analysis
- **TotalValue vs. Quantity**: Strong correlation (higher quantity drives revenue).
- **Price vs. Quantity**: No significant correlation.
- **Takeaway**: Prioritize increasing sales volume over price hikes.

---

## Key Takeaways
1. **Customer Base**: South America dominates, but North America has the highest AOV.
2. **Product Focus**: Expand Electronics (most profitable) and improve Home Decor offerings.
3. **Revenue Growth**: Boost AOV via bundling/upselling and focus on high-revenue products.
4. **Marketing**: Target underpenetrated regions (North America) and retain high-value customers.
5. **Pricing**: Avoid price increases; instead, bundle products to drive volume.

---

**Note**: Detailed visualizations (e.g., bar plots, histograms) are available in the [EDA report PDF](prashanthkt_EDA.pdf).  
**Script**: Analysis performed using `Prashanth_K_T_EDA.py`.
