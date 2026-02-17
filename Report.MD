```markdown
# 📊 Project Report: Customer Shopping Analytics – Retail Performance & Consumer Behavior

---

## Project Title
Customer Shopping Analytics – Retail Performance & Consumer Behavior

---

## Business Problem / Objective
Retailers and mall operators in Istanbul face the challenge of understanding:
- Customer shopping behavior and preferences.
- Top-performing malls and product categories.
- Purchasing patterns across age, gender, and payment methods.
- Opportunities to optimize product placement, promotions, and mall strategies.

**Key Questions:**
- Who are the customers, and how do they shop?
- Which malls and product categories drive the most revenue?
- How do sales and orders trend over time?
- Which customers are high-value vs low-value, and what opportunities exist to increase revenue from each segment?

**Challenge Solution:** Grouped customers into Low, Medium, and High spenders using a Customer Summary table to identify top and bottom customers.

---

## Dataset Overview
| Attribute | Details |
|-----------|---------|
| Source | Retail transaction dataset from EasyTech Talent Challenge |
| Scope | Transactions across 10 major shopping malls in Istanbul |
| Time Period | 2021–2023 |
| Key Columns | Customer demographics (age, gender), Product category, Quantity, Price, Revenue, Payment method, Shopping mall, Invoice date |
| Records | Tens of thousands of transactions |

---

## Tools Used
- Microsoft Power BI – Data modeling, DAX measures, dashboard visualization
- Excel – Initial cleaning, exploration, and aggregation
- PowerPoint – Wireframing dashboard layout and planning visuals

---

## Data Cleaning & Preparation
- Removed duplicate invoices and standardized date formats
- Created DimDate and other dimension tables: Customer, Mall, Category, Payment, Date
- Handled missing values in demographics
- Created calculated measures: Revenue, Orders, Quantity, AOV, MoM, YoY
- Created Customer Summary table to group customers into Low, Medium, High spenders

**Business Analyst Thinking:** Grouping customers allows strategic segmentation for targeted promotions and retention campaigns, rather than analyzing raw customer IDs individually.

---

## Challenges Faced
- Identifying top and bottom customers was difficult because the raw data lacked clear segmentation.
- Creating the Customer Summary table with Low, Medium, and High spenders resolved this issue and enabled effective grouping.
- Wireframing the dashboard in PowerPoint before building it in Power BI helped plan a **logical layout**, improve readability, and ensure executive-ready visualization flow.

---

## Key Questions & Analysis
### Customer Behavior
- Who are our customers by age and gender?
- Which payment methods are preferred?
- Which customers contribute most to revenue?

### Sales Performance
- How do sales and orders trend over time?
- Which malls perform best and which are declining?
- How does Average Order Value (AOV) vary by mall?

### Category Insights
- Which categories generate the most revenue and volume?
- Which categories are growing or declining?
- Which categories should be prioritized for promotions?

### Segmentation Insights
- Distribution of Low, Medium, High spenders across malls and categories
- Revenue contribution of top vs bottom customers

---

## Key Insights
### Customer Behavior
- Majority of customers are aged 20–40
- Credit card is the most preferred payment method
- Top 10 customers contribute ~30% of total revenue
- Medium and Low spenders present growth opportunities

### Sales Performance
- Revenue shows seasonal peaks with steady MoM growth
- Mall of Istanbul and Kanyon lead in revenue; Emaar Square Mall has the highest AOV
- Some malls are declining and need targeted retention campaigns

### Category Insights
- Clothing, Shoes, Technology dominate revenue
- Cosmetics and Toys show growth potential
- Food & Beverage has high volume but low AOV (upselling opportunity)

### Customer Segmentation Insights
- Customer grouping allows targeted promotions and retention strategies
- Medium and Low spenders are concentrated in high-traffic malls

---

## Recommendations
### Customer Strategies
- Focus loyalty programs on high spenders
- Incentivize Low and Medium spenders to increase frequency and basket size

### Mall Strategies
- Promote declining malls through targeted campaigns
- Replicate successful strategies from top-performing malls

### Category Strategies
- Upsell in Food & Beverage
- Promote declining categories (e.g., Books)
- Maintain momentum in Electronics

### Monitoring & Reporting
- MoM metrics for short-term performance monitoring
- YoY metrics for long-term strategic planning

---

## Dashboard / Visualization Layout
| Page | Focus | Visuals |
|------|-------|---------|
| Page 1 | Customer Demographics & Behavior | Age/Gender distribution, Payment preferences, Top/Bottom customer segments |
| Page 2 | Revenue & Mall Performance | Monthly revenue trend, Mall comparisons, Weekly sales distribution |
| Page 3 | Category Insights | Revenue by category, Growth/Decline trends, Gender-based preferences, Top 5 categories line chart |

**Wireframing:** PowerPoint used to plan layout and visual placement before building in Power BI.

---

## Conclusion
Provides a 360° view of customers, malls, and categories:
- Improves customer loyalty and retention
- Optimizes mall promotions and strategies
- Prioritizes top-performing categories
- Enables targeted marketing campaigns using customer segmentation

**Business Impact:** Supports data-driven decisions to increase revenue, improve customer satisfaction, and optimize operations

---

## Limitations
- No marketing spend or external economic factors included
- Customer demographics limited to age and gender
- MoM and YoY trends may be affected by irregular transactions

---

## About Me
I am an **E-commerce Data Analyst** with experience in retail analytics, customer segmentation, and Power BI dashboarding. I help businesses understand customer behavior, optimize category and mall strategies, and drive revenue growth through data-driven insights. My skills include advanced DAX, data modeling, and actionable visualization storytelling.

---

## Documentation Approach
- Written in business language for executives
- Avoided technical jargon; focused on business impact
- Bullet points used for readability
- Highlighted analytical methodology, challenges, and strategic recommendations
```
