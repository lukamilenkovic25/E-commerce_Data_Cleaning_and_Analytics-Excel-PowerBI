# E-commerce-Data-Analytics-Portfolio

## Project Overview
This project simulates a real-world E-commerce dataset intentionally created in a raw, dirty, and inconsistent state in order to practice data cleaning, transformation, and exploratory analysis using Microsoft Excel.
The primary goal of the project was to demonstrate how messy business data can be transformed into a clean, structured dataset suitable for analysis and decision-making.

---

## About Me
I am a Junior Data Analyst with a strong focus on Power BI, DAX, and business-oriented analytics.  
My work emphasizes clean data preparation, optimized data modeling, KPI development, and transforming raw data into actionable insights that support decision-making.

---

## Dataset Description
The dataset represents E-commerce transactional data containing:
- Orders and order dates
- Customer information
- Sales channels
- Product categories
- Revenue and currency values
- Order status
- Delivery performance metrics

The raw data includes typical real-world data quality issues such as:
- inconsistent naming conventions
- missing and unknown values
- mixed date formats
- numeric values stored as text
- inconsistencies across regions, products, and order statuses
  
---

## Tools and Techniques Used
**Microsoft Excel**

Key skills demonstrated:
- Data cleaning and normalization
- Data standardization using mapping tables
- Column-by-column transformation (raw vs cleaned columns)
- Handling missing and inconsistent values
- Text-to-number conversion
- Date format standardization
- Pivot Tables for analysis
- KPI calculation
- Dashboard creation

---

## Data Cleaning Approach

For full transparency, **each raw column has a corresponding cleaned column**, allowing direct comparison between original and standardized values.
Examples of data transformations:
- `order_id` → standardized order format
- `region` → unified region values (USA, Europe, Asia)
- `product` → standardized product categories
- `quantity` → text values (“two”, “five”) converted to numbers
- `revenue` → numeric extraction from mixed currency strings
- `order_status` → unified statuses (Delivered, Pending, Returned)
- `delivery_days` → converted into consistent numeric values
A dedicated **Mappings sheet** was used to ensure scalable and maintainable transformations instead of hard-coded fixes.

---

## KPI Dashboard
**Key Metrics**:
- Total Revenue
- Total Orders
- Return Rate %
  
The dashboard provides a quick overview for stakeholders and highlights potential operational issues.

---

## Business Insights

- **High Return Rate**
  The overall return rate is close to 47%, which is unusually high for E-commerce operations. This suggests potential issues such as product quality mismatches, unclear product descriptions, or logistics-related problems.

- **Revenue Concentration by Region** 
  The majority of revenue comes from USA and Europe, indicating these regions as the primary revenue drivers and key focus areas for business growth.

- **Product Category Risk Differences**
  Certain high-revenue product categories also exhibit elevated return frequency, suggesting customer expectation gaps or product-related issues.

- **Delivery Performance Impact**
  Orders with longer delivery times appear more frequently among returned or problematic orders, indicating a possible relationship between delivery delays and customer satisfaction.

These insights demonstrate how structured and well-cleaned data enables actionable business conclusions, which would not be possible using the raw dataset.

---

## Purpose of This Portfolio
After cleaning and analyzing the data, several business-relevant insights emerged:
- real‑world data challenges
- sound analytical judgment
- clarity of insights
- professional data handling standards

---

## Contact
- LinkedIn: https://www.linkedin.com/in/luka-milenkovic-74768a285
- Email: m.milenkovicluka@gmail.com 
- GitHub: https://github.com/lukamilenkovic25

---
