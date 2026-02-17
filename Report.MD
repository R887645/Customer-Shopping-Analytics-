# 📊 Customer Shopping Analytics: Retail Performance & Consumer Behavior Across 10 Major Istanbul Malls

---

## Business Problem / Objective

A mall operator managing 10 major shopping malls in Istanbul needed clarity on performance drivers and growth risks.

The business wanted to understand:

- Which customer segments drive the most revenue?
- Which malls and product categories are outperforming or declining?
- How revenue is trending month-over-month (MoM) and year-over-year (YoY)
- Where the strongest opportunities exist for growth and retention

The objective of this analysis was to transform transactional retail data into actionable business insights to support strategic decision-making.

---

## Dataset Overview

- Source: Retail transactional dataset (EasyTech Power BI Challenge)
- Time Period: 2021–2023
- Coverage: 10 major shopping malls in Istanbul
- Data Type: Customer transactions
- Key Columns:
  - Invoice Date
  - Customer Age & Gender
  - Product Category
  - Shopping Mall
  - Quantity
  - Revenue
  - Payment Method

The dataset captures multi-location performance, customer demographics, and category-level revenue trends.

![My Image Description}(https://github.com/R887645/Customer-Shopping-Analytics-/blob/main/Main%20Dataset_Customershoopping.png?raw=true)
---

## Tools Used

- Excel and Power Query– Data inspection, cleaning, and validation
- Power BI – Data modeling, DAX calculations, dashboard development
- PowerPoint – Wireframing dashboard layout before development

---

## Data Cleaning & Preparation

- Removed duplicate transactions per dimensional Tables
- Standardized date formats using Local, Format other columns necessary as well.
- Extract dimensional tables across (Customer, Order, Mall, Category, Payment)

![My Image Description](https://github.com/R887645/Customer-Shopping-Analytics-/blob/main/customr_shopping_Data%20Cleaning.png?raw=true)

- Created a Calendar Table for time intelligence.
- Connected the dimensional data models across (Customer, Order, Mall, Category, Payment) to the Fact Table
![My Image Description](https://github.com/R887645/Customer-Shopping-Analytics-/blob/main/Customer%20shopping_Data%20Modelling.png?raw=true)

- Created DAX measures:
  - Total Revenue
  - Orders & Quantity
  - Average Order Value (AOV)
  - MoM Growth
  - YoY Growth and lots more
- created a Product Categories table that has unique categories with reference URLs from Pinterest
- Did some grouping for Age Range in particular

![My Image Description](https://github.com/R887645/Customer-Shopping-Analytics-/blob/main/Customer%20shopping_DAX.png?raw=true)

This ensured the analysis was structured, scalable, and decision-ready.

---

## Key Questions & Analysis

- Which customer age groups contribute the highest revenue?
- Which malls generate the strongest performance?
- Which categories dominate revenue contribution?
- Are there performance risks due to over-reliance on certain malls or segments?
- What are the observable seasonal and weekly sales patterns?

---

# 📊 Key Findings

## Home Page
- An overview of what the analysis is about, and navigation buttons to get across to all the pages
![My Image Description](https://github.com/R887645/Customer-Shopping-Analytics-/blob/main/Customer_Shopping_Homepage.png?raw=true)

## Customer Behaviour Insights

- Total revenue grew to **$251.5M**, up **9.35% YoY**
- Orders and quantities increased by approximately 9%
- The **51+ age group (36K customers)** contributes the highest revenue share
- Customers aged **21–40** form a strong secondary base critical for long-term growth
- Gender contribution is balanced across segments
- Digital payments dominate:
  - Credit Card: 44.7%
  - Debit Card: 35.1%
  - Cash: 20%
- Metrocity (15K customers) and Metropol AVM (10.2K) attract the highest customer traffic
- Revenue shows seasonal fluctuations with clear expansion and contraction cycles

![My Image Description](https://github.com/R887645/Customer-Shopping-Analytics-/blob/main/Customer_Shopping_Customer%20analysis.png?raw=true)

---

## Sales Performance

- Total revenue across 10 malls (2021–2023): **$221.6M**
- Average Order Value: **$221.6K**
- Top-performing malls:
  - Mall of Istanbul ($52M)
  - Kanyon ($47M)
  - Emaar Square Mall ($42M)
- Bottom Performing malls:
  - (Cevahir AVM, Emaar Square, Forum Istanbul, Viaport Outlet, Zorlu Center)
- Best-selling categories:
  - Clothing ($57M)
  - Shoes ($50M)
  - Technology ($41M)
- Some malls show declining YoY revenue, indicating over-reliance on high-performing locations

![My Image Description](https://github.com/R887645/Customer-Shopping-Analytics-/blob/main/Customer_Shopping_Sales.png?raw=true)

---

## Category Insights

- Clothing, Shoes, and Technology dominate total revenue
- Food & Beverage has high transaction volume but low AOV → Upsell opportunity
- Cosmetics and Toys show emerging growth potential
- The books category is declining and requires promotional intervention

![My Image Description](https://github.com/R887645/Customer-Shopping-Analytics-/blob/main/Customer_Shopping_Category.png?raw=true)

---

# Strategic Recommendations

- Develop targeted campaigns for younger professionals (21–40) to secure long-term growth
- Launch digital-first loyalty programs (cashback, points, app-based rewards)
- Strengthen marketing and events in low-performing malls (Forum, Emaar Square) to reduce over‑reliance on top performers.
- Reduce performance dependency on top-performing malls
- Align promotions with:
  - Weekly sales spikes (Monday & Saturday)
  - Seasonal peaks (January & October)

---

## Dashboard Overview

The Power BI dashboard provides:

- Customer demographic breakdown
- Mall-level performance comparison
- Category revenue analysis
- MoM and YoY growth tracking
- Customer segmentation insights
- Easy navigation of the dashboard using Slicr and resetting Bookmarks

[View the Full Interactive Dashboard Here](https://app.powerbi.com/view?r=eyJrIjoiY2QxNmU3NDEtYWFiMS00MDYzLTk2YzEtNjc1YjkyZDk5NDM5IiwidCI6ImZjY2Y0MmRmLTE2ZDktNGU4Ny1hNmUwLWU0OTYyMjAxN2Y3NCJ9)

Designed for executive-level decision support and performance monitoring.


---

## Limitations

- The dataset does not include marketing spend
- No customer income or behavioral loyalty data available
- External economic factors were not included in the analysis
- Doesn't include the real customer names, and some customers bought the same amount of products, making it hard to do that particular analysis (Top customers and bottom-performing customers)

---

## Conclusion

This analysis identified key revenue drivers, performance risks, and growth opportunities across 10 major malls in Istanbul.

By combining customer segmentation, category performance analysis, and trend tracking, the business can make informed decisions to optimize revenue and reduce operational risk.

---

## About Me

I am your E-commerce Data Analyst specializing in Marketing and sales analytics, and Power BI dashboard development.

I help businesses transform transactional data into strategic insights that drive measurable growth, support executive decision-making, and more.
