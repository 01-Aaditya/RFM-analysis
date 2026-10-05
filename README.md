# E-Commerce RFM Customer Segmentation

End-to-end customer segmentation project using RFM analysis on a large retail transaction dataset, followed by an interactive Power BI dashboard.

---

## Project Overview

This project analyzes customer purchasing behavior from a UK-based online retailer (2009–2011) using the RFM framework (Recency, Frequency, Monetary).  

The goal is to segment customers into actionable groups so that marketing and retention strategies can be targeted more effectively.

**Dataset:** Online Retail II (UCI)  
**Clean records:** ~397,000 transactions  
**Unique customers:** 5,878  
**Tools:** Python (Pandas, Seaborn) + Power BI

---

## Key Insights

- **Champions** (top segment) make up ~30% of customers but generate the majority of revenue
- Clear seasonal pattern: strong revenue spike every November (Q4)
- High returns rate (~17.6%) — important for inventory and customer experience analysis
- Thursday is the strongest day for orders; Sunday is almost inactive
- A small group of high-value customers drives a large share of total revenue

---

## Project Phases

### Phase 1 – Data Cleaning & EDA
- Removed missing Customer IDs, duplicates, and invalid transactions
- Separated cancelled invoices for returns analysis
- Explored revenue trends, top products, top countries, and order patterns

### Phase 2 – RFM Scoring & Segmentation
- Calculated Recency, Frequency, and Monetary values for every customer
- Scored each dimension from 1–5
- Created clear customer segments: Champions, Loyal, Potential Loyal, At Risk, Lost

### Phase 3 – Power BI Dashboard
Interactive 3-page dashboard covering:
- Executive Overview (KPIs, trends, top markets & products)
- RFM Segments (distribution and revenue contribution)
- Product Analysis (top products, heatmap, day-of-week patterns)

---

## Tech Stack

| Tool          | Purpose                          |
|---------------|----------------------------------|
| Python        | Data cleaning, EDA & RFM scoring |
| Pandas / NumPy| Data manipulation                |
| Seaborn / Matplotlib | Visualizations              |
| Power BI      | Interactive dashboard            |

---

## How to Explore

1. Review the Jupyter notebooks for the full analysis process
2. Open the Power BI file (or view the PDF version) to explore the dashboard
3. Check the RFM scored data and segment summary files

---

## Skills Demonstrated

- Customer segmentation using RFM methodology
- Large-scale retail data cleaning and exploration
- Business-oriented insight generation
- Interactive dashboard design in Power BI
- End-to-end analytics workflow (Python → Power BI)

---

## Future Improvements

- Add predictive models for customer lifetime value (CLV)
- Build automated segment update pipeline
- Create personalized marketing recommendations based on segments
