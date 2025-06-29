# 🛍️ Online Retail Sales Analysis

This project analyzes online retail data to uncover trends in revenue, customer value, country performance, and expansion opportunities using Power Bi. It was designed to answer four strategic business questions from the CEO and CMO.

## 📊 Project Objectives
- Understand monthly revenue trends over 2011.
- Identify top-performing countries outside the UK.
- Highlight top customers by revenue.
- Pinpoint countries with the highest product demand.

## 🧼 Data Cleaning Process
- Removed rows where `Quantity < 1` and `UnitPrice < $0`.
- Created a `Revenue` column as `Quantity × UnitPrice`.
- Cleaned data was used for visualizations and insights.

## 👔 CEO Question 1: Monthly Revenue Trends
**Tool Used**: Line Chart  
- Steady growth throughout the year.  
- Peak in **November ($1.5M)**.  
- Decline in December due to early shopping behavior.  
> 📌 *Insight:* Clear seasonality — strong Q4 performance.

## 🌍 CMO Question 2: Top Countries by Revenue
**Tool Used**: Clustered Column Chart  
- Netherlands and EIRE lead with **$280K+ revenue**.  
- Western Europe shows consistent strength.  
> 📌 *Insight:* Focus on Western Europe for expansion.

## 👥 CMO Question 3: Top Customers by Revenue
**Tool Used**: Area Chart  
- Top 2 customers (IDs 14646 & 18102) contribute **$280K+** each.  
- Significant drop-off after the top 3.  
> 📌 *Insight:* Prioritize high-value customers for loyalty programs.

## 🌎 CEO Question 4: Product Demand by Country
**Tool Used**: Clustered Column Chart  
- Netherlands, EIRE, Germany lead in demand.  
- Australia and some Asian countries show potential.  
> 📌 *Insight:* Target Western Europe and Australia for growth.

## 🚀 Strategic Takeaways
- Strong Q4 seasonality – ideal for campaign planning.
- Top 3 countries dominate both revenue and demand.
- High customer concentration — retention is key.
- Visuals help balance margin (revenue) vs. volume (demand).

## 📁 Files Included
- `Retail_Analysis_Presentation.pdf` — presentation summary
- `cleaned_data.xlsx` — cleaned dataset
- `README.md` — this documentation

## 🙌 Thank You
This analysis forms a strong foundation for strategic planning, customer targeting, and international expansion efforts.
