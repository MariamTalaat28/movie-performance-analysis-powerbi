# Movie Performance Analysis – Power BI

End-to-end movie industry analysis using **Power BI**, including data cleaning, data warehousing (star schema), KPI dashboards, and decision-support insights.

---

## Project Overview
This project analyzes movie performance data to understand how **budget, genre, ratings, and release factors** impact **global revenue and profitability**.  
The goal is to support **data-driven decision-making** in the movie industry.

---

## Tools & Technologies
- Power BI
- Power Query (Data Cleaning & Transformation)
- DAX (Measures & KPIs)
- Star Schema Data Warehouse Design

---

## Data Preparation
- Removed duplicates and handled missing values  
- Text cleaning using **Trim** and **Clean**
- Outlier detection using:
  - **Z-Score** (for revenue and budget)
  - **IQR method** (for ratings and sales)
- Created outlier flags for analysis and filtering

---

## Data Warehouse Design
- Implemented a **Star Schema** model
- Fact Table:
  - `FactMoviePerformance`
- Dimension Tables:
  - `DimGenre`
  - `DimCountry`
  - `DimDirector`
  - `DimDate`
  - `DimMovie`

---

## Key DAX Measures
- Total Global Revenue
- Total Budget
- Total Profit
- ROI %
- Average IMDb Rating
- Average Rotten Tomatoes Score

---

## Dashboards
### Dashboard 1 – Executive KPI Overview
- Total Global Revenue
- Total Budget
- Total Profit
- ROI %
- Average IMDb & Rotten Tomatoes Scores

### Dashboard 2 – Movie Performance Analysis
- Revenue by Genre
- Budget vs Revenue
- Top 10 Movies by Opening Day Sales
- Revenue Trends Over Time
- Profitability by Country

---

## Key Insights
- **Drama and Comedy** are the strongest genres in both revenue and ratings  
- **Horror** delivers high ROI despite low budgets  
- **Action** performs well but requires cost optimization  
- **Documentary and Sci-Fi** underperform financially  

---

## Business Recommendations
- Increase investment in **Drama and Comedy**
- Expand **low-budget Horror** productions
- Control budgets for **Action** movies
- Apply targeted marketing for **Thriller and Romance**
- Reevaluate high-cost **Sci-Fi and Documentary** projects

---

## Author
**Mariam Talaat**  
Aspiring Data Analyst / Business Intelligence Analyst
