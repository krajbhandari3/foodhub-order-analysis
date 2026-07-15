# FoodHub Order Analysis

## Business Problem
FoodHub, a food aggregator platform, needed to understand ordering patterns, 
customer behavior, and operational bottlenecks from their transaction data 
to improve business performance and customer experience.

## Approach
- Performed exploratory data analysis (EDA) using Python (Pandas, NumPy) 
  to understand order volume, cuisine preferences, delivery times, and 
  customer ratings
- Conducted univariate and multivariate analysis to identify key patterns
- Investigated relationships between delivery time, food preparation time, 
  and customer ratings
- Identified missing values and outliers in the dataset

## Key Findings
- Analyzed 1,898 orders across 14 cuisine types with no duplicate records
- American (584 orders) and Japanese (470 orders) cuisines dominate, 
  together representing 56% of all orders
- 71% of orders occur on weekends vs. 29% on weekdays — a significant 
  demand skew
- Average total order time is ~52 minutes (27 min prep + 24 min delivery); 
  200 orders (11%) exceeded 60 minutes
- 39% of orders (736) have no customer rating — a major data gap
- Among rated orders, 88% received a rating of 4 or 5 — but delivery 
  speed showed no correlation with rating, suggesting other factors 
  drive satisfaction

## Business Recommendations
- **Close the rating gap:** With 39% of orders unrated, FoodHub is 
  missing a large share of customer feedback. Recommend implementing 
  a strategy (e.g., post-delivery prompts, incentives) to capture ratings
- **Staff for weekend demand:** Since 71% of orders occur on weekends, 
  delivery and kitchen staffing should be weighted accordingly to reduce 
  delays during peak periods
- **Address the 11% of slow orders:** Investigate root causes behind 
  orders exceeding 60 minutes total time and target process improvements 
  to bring these under threshold
- **Deepen restaurant partnerships:** American and Japanese cuisines 
  drive the majority of volume — prioritize these partnerships for 
  promotions and reliability improvements
- **Look beyond speed for satisfaction drivers:** Since delivery speed 
  didn't correlate with rating, consider surveying customers directly 
  to identify what actually drives satisfaction (food quality, order 
  accuracy, etc.)

## Tools Used
Python, Pandas, NumPy, Matplotlib/Seaborn

## Background
Completed as part of the Post Graduate Program in AI & Machine Learning 
(UT Austin McCombs School of Business). Prior professional background is 
in Power BI/Business Intelligence — this project reflects the same EDA 
thinking applied through Python rather than Power Query/DAX.
