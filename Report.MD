# Customer Shopping Analytics: Retail Performance & Consumer Behavior Across 10 Major Istanbul Malls

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
  - Revenue (Price)
  - Payment Method

The dataset captures multi-location performance, customer demographics, and category-level revenue trends.

![My Image Description](https://github.com/R887645/Customer-Shopping-Analytics-/blob/main/Customer_Shopping_Maindataset.png?raw=true)
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

## Customer Behavior Insights

- Revenue grew **9.35% YoY**, driven by increases in order volume and quantities purchased.
- The **51+ age group dominates revenue (~₺24.8M)**, representing the most financially impactful segment.
- Younger professionals (**21–40**) show steady growth and represent long-term sustainability potential.
- **Credit cards (44.7%)** are the most preferred payment method, while cash accounts for 20%, signaling strong digital adoption.
- **Metrocity, Mall of Istanbul, and Kanyon** attract the highest customer traffic.

![My Image Description](https://github.com/R887645/Customer-Shopping-Analytics-/blob/main/Customer_Shopping_Customer%20analysis.png?raw=true)

---

## Sales Performance Analysis

- **Total Revenue:** ₺68.55M  
- **Average Order Value (AOV):** ~₺689 (stable across locations)
- The **Top 5 malls** (Mall of Istanbul, Kanyon, Metrocity, Metropol AVM, Istinye Park) generate the majority of total revenue.
- The **Bottom 5 malls** (Cevahir, Emaar Square, Forum Istanbul, Viaport, Zorlu) each generate approximately ~₺3.3M, reflecting weaker traffic despite similar AOV.
- Sales peak on **Monday and Saturday**, with seasonal highs in **January and October**.
- Some malls show declining YoY revenue, indicating over-reliance on high-performing locations

![My Image Description](https://github.com/R887645/Customer-Shopping-Analytics-/blob/main/Customer_Shopping_Sales.png?raw=true)

---

## Category Insights

- **Clothing (₺31M), Shoes (₺18M), and Technology (₺16M)** dominate total revenue contribution.
- Female customers account for approximately **60% of total spending** across categories.
- Cosmetics and Toys underperform relative to their broader market potential.
- Monthly category trends reveal seasonal spikes but uneven growth across segments.

![My Image Description](https://github.com/R887645/Customer-Shopping-Analytics-/blob/main/Customer_Shopping_Category.png?raw=true)

---

# Strategic Recommendations

## 1️⃣ Target Younger Professionals for Sustainable Growth

Develop tailored campaigns for the **21–40 segment** focused on fashion, technology, and lifestyle products to sustain long-term revenue beyond the 51+ demographic.

## 2️⃣ Expand Digital-First Loyalty Programs

Introduce cashback rewards, points-based systems, and app-exclusive promotions to:
- Reduce reliance on cash
- Increase repeat purchases
- Improve customer retention

## 3️⃣ Strengthen Underperforming Malls

Increase marketing efforts and in-mall events in **Forum Istanbul, Emaar Square, Viaport, and Zorlu** to balance performance and reduce over-reliance on Mall of Istanbul and Kanyon.

## 4️⃣ Optimize Category Strategy

Double down on high-performing categories (**Clothing, Shoes, Technology**) while repositioning weaker categories (**Cosmetics, Toys, Books**) using bundled offers and targeted promotions.

## 5️⃣ Align Promotions with Demand Peaks

Schedule campaigns, product launches, and upsell strategies around:
- High-traffic days (**Monday & Saturday**)
- Seasonal demand spikes (**January & October**)

This ensures marketing spend is aligned with natural revenue acceleration periods.

---

## Dashboard Overview

The Power BI dashboard provides:

- Customer demographic breakdown
- Mall-level performance comparison
- Category revenue analysis
- MoM and YoY growth tracking
- Customer segmentation insights
- Easy navigation of the dashboard using Slicr and resetting Bookmarks

[View the Full Interactive Dashboard Here](https://app.powerbi.com/view?r=eyJrIjoiMzEwMjUyMTItMTAyZS00MmFmLWEzMGItYTA1N2E0MDc4OGQ3IiwidCI6ImZjY2Y0MmRmLTE2ZDktNGU4Ny1hNmUwLWU0OTYyMjAxN2Y3NCJ9)

[Checkout the full slides of this report](https://drive.google.com/file/d/1bFaQ6NIMryTsN9eyvMhe3oB713akAw4R/view?usp=sharing)

Designed for executive-level decision support and performance monitoring.


---

## Limitations

- The dataset does not include marketing spend
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
