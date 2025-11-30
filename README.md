# 📊 Superstore Returns Analysis Dashboard

## Overview
This project explores customer returns data from the Superstore dataset to evaluate how returns impact sales and profit. Using Tableau, I built an interactive dashboard that highlights key return metrics, root causes, and their financial implications. The project was completed as part of my Data Analytics program at TripleTen.

🔗 [View the Dashboard on Tableau Public](https://public.tableau.com/app/profile/marlon.romero3289/viz/SuperstoreReturnsAnalysis_Story/CustomerReturnsDashboard#1)

---

## Dataset
- **Source:** Superstore dataset (provided by TripleTen)  
- **Tables Used:** Orders, Returns, People  
- **Key Columns:** Order ID, Returned (Yes/No), Sales, Profit, Category, Region, Segment  

---

## Objectives
- Determine how returns should be measured: return rate, total number of returns, or total cost of returns.  
- Identify key root causes of returns across categories and regions.  
- Provide visual insights into how returns affect profitability.  

---

## Dashboard Components
The dashboard combines multiple chart types to give a complete view of customer returns:

- **Bar Chart:** Compares return rates across product categories.  
- **Line Chart:** Tracks trends in return rates over time.  
- **Scatter Plot:** Displays the relationship between profit and returns.  
- **Geographical Map:** Highlights regions with the highest return costs and frequency.  

Each chart includes tooltips and filters to allow interactive exploration of the data.  

---

## Key Insights
- Technology products show higher return rates, but they also drive strong profit margins.  
- Certain regions experience significantly higher return costs, indicating possible supply chain or quality issues.  
- Seasonal spikes in returns align with high-sales periods, such as end-of-year holidays.  

---

## Tools & Methodology
- **Tool Used:** Tableau  
- **Process:**  
  - Joined Orders and Returns tables using a left join on `Order ID`.  
  - Built calculated fields for Return Rate and Profit Impact.  
  - Designed and combined bar, line, scatter, and geographical charts into a cohesive dashboard.  


