# Consumer Behavior Analysis Project

> For more of my projects and analytics journey, visit my [Portfolio](https://pvenetis.github.io/).

### Table of Contents
- [Project Overview](#project-overview)
- [Data Structure Overview](#data-structure-overview)
- [Executive Summary](#executive-summary)
- [Insights Deep Dive](#insights-deep-dive)
- [Recommendations](#recommendations)
- [Data & Analysis Artifacts](#data--analysis-artifacts)

---

## Project Overview

This project analyzes customer shopping behavior using transactional data from **3,900 purchases** across multiple product categories.  
The goal is to uncover:
- Spending patterns  
- Customer segment behavior  
- Product preferences  
- Subscription differences  
- Factors influencing purchasing decisions  

The analysis supports better decisions across **marketing**, **inventory**, and **customer engagement** strategies.

---

## Data Structure Overview

**Dataset Summary**
- **Rows:** 3,900  
- **Columns:** 18  

**Key Features**
- **Customer Demographics:**  
  `age`, `gender`, `location`, `subscription_status`
- **Purchase Details:**  
  `item_purchased`, `category`, `purchase_amount`, `season`, `size`, `color`
- **Shopping Behavior:**  
  `discount_applied`, `previous_purchases`, `purchase_frequency_days`, `review_rating`, `shipping_type`
- **Feature Engineering / Cleaning:**  
  Missing values in `review_rating` were imputed with category medians.  
  Added `age_group` and `purchase_frequency_days` columns for segmentation and analysis.

This cleaned and enhanced dataset was used for customer segmentation, revenue analysis, seasonal trends, and behavior-based insights.

---

## Executive Summary

The analysis highlights several key trends:

- **Revenue concentration** is strongest in Clothing and Accessories.
- **Subscribed customers** tend to exhibit higher overall engagement.
- **Review ratings correlate with spending**, with higher ratings linked to higher purchase amounts.
- **Seasonality is influential**, especially in apparel-related categories.
- **Item size preferences** show strong clustering, guiding merchandising decisions.
- **Discounts boost order quantity**, but full-price purchases often have higher average value.

---

## Insights Deep Dive

### 1. Subscription Behavior
- Subscribed customers form a minority of the base but demonstrate **stronger purchase consistency**.
- Non-subscribed customers contribute a larger share of one-time orders.

### 2. Rating–Spend Relationship
- Scatter plot analysis shows a **positive relationship** between review ratings and average purchase amount.
- Customers giving 4–5 star ratings tend to be **higher-value** buyers.

### 3. Seasonal Purchase Patterns
- Fall and Winter drive the highest order volume, especially in apparel categories.
- Summer shows lower volume but strong performance in lightweight items.

### 4. Product Size Trends
- Majority of purchases are **M** and **L**, indicating core inventory demand.
- Smaller and larger sizes (S, XL) represent niche but essential inventory segments.

### 5. Discount Impact
- Discounts increase **volume**.
- Average order value remains **higher for non-discounted** purchases.
- Targeted promotions outperform blanket discounting.

---

## Recommendations

- **Expand subscription incentives** to convert high-potential repeat buyers.
- **Encourage review participation** to strengthen loyalty and improve predictive accuracy of customer value.
- **Adjust marketing calendars** to match seasonal demand peaks.
- **Focus inventory** on high-demand sizes while maintaining coverage for edge sizes.
- **Use targeted discounts** to maintain margins without sacrificing volume.

---

## Data & Analysis Artifacts

**Access the data and analysis files used in this project:**

- 📊 [Python Notebook](./python/customer_shopping_behaviour_analysis.ipynb)  
- 🧾 [Raw and Clean Dataset](./data)  
- 📈 [Power BI Dashboard Screenshot](./powerbi/style_mart_customer_behaviour_dashboard.PNG)  
- 💻 [SQL Queries](./sql/StyleMart%20EDA.sql)

---

*© 2025 Peri Venetis – Customer Behavior Analysis Project*
