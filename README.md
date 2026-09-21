# 🛍️ Retail Customer Review Rating Analysis (Power BI)

An interactive Power BI dashboard that analyzes retail customer reviews and purchasing behavior to understand how satisfaction varies across customer segments, product categories, and seasons.

---

## 🔍 Overview
Customer reviews are a direct signal of service and product experience. This project builds an interactive Power BI dashboard on top of retail customer data to explore how review ratings relate to purchase amount, subscription status, demographics, product category, and season.

## 🎯 Business Questions
- How satisfied are customers overall, and how does satisfaction differ by age group?
- Which product categories drive the most purchase value?
- How does purchase value change across seasons?
- What share of customers are subscribed, and does subscription matter?
- Is there a relationship between a customer's previous purchases and their current purchase amount?

## 📊 Dashboard Preview
<img width="1355" height="752" alt="Screenshot 2026-08-30 215406" src="https://github.com/user-attachments/assets/c4d974ab-1dba-4b4d-9c64-531f7f4a9787" />

**Interactive slicers:** Subscription status · Gender · Product category

## 📂 Dataset
- **Records:** ~3,900 customers
- **Key fields:** `customer_id`, `age group`, `gender`, `category`, `purchase_amount`, `previous_purchases`, `review_rating`, `subscription_status`, `season`

## 📈 Key Metrics
| Metric | Value |
|---|---|
| Number of customers | **3.9K** |
| Average purchase amount | **$59.76** |
| Average review rating | **3.75 / 5** |
| Subscribed customers | **27%** |

## 💡 Key Insights
- **Clothing leads revenue:** Clothing (~104K) is the top category by total purchases, followed by Accessories (~74K), Footwear (~36K), and Outerwear (~19K).
- **Low subscription adoption:** Only 27% of customers are subscribed, so 73% are a potential conversion opportunity.
- **Young adults rate highest:** Young Adults give the highest average rating (~3.80), and ratings decline for other age groups, with Middle-aged customers lowest (~3.71).
- **Seasonality:** Purchase value peaks in Fall and dips in Summer, the weakest season.
- **Ratings are moderate overall:** An average of 3.75 leaves clear room to improve satisfaction.
- [Add any insight from the slicers, e.g., differences by gender or subscription status]

## ✅ Recommendations
- Run **subscription campaigns/loyalty offers** to convert the 73% non-subscribers.
- Investigate why **older and middle-aged segments** rate lower and tailor product or service improvements for them.
- Boost **Summer** with targeted promotions or seasonal product lines.
- Double down on **Clothing and Accessories** while reviewing whether **Outerwear** needs repositioning outside colder months.

## 🛠️ Tools & Technologies
- **Power BI Desktop** – data modeling, DAX measures, visuals
- [Excel / SQL / Power Query – for cleaning, if used]
- Git & GitHub – version control
