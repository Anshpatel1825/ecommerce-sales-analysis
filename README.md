# E‑Commerce Sales Analysis Project
- An end‑to‑end exploratory data analysis and visualization project, uncovering actionable insights across sales, profit, discounts, segments, and regions.

 # Project Objective & Business Impact
 - dentifying high-revenue categories, customer segments, and regions
 - Highlighting underperforming areas
 - Understanding the impact of discounting on profit margins
 - Supporting better pricing, promotion, and inventory strategies

# Tools & Libraries
- Python: Pandas, NumPy, Matplotlib, Seaborn
- Notebook: Jupyter
- Charts: Heatmaps, Bar Charts, Scatter Plots

# Visualizations & Insights

# 1>Univariate Analysis (Single Column)
  ## 1> Ship Mode vs Order Count
- Purpose: Understand which shipping modes are most preferred by customers.
  ![ Ship Mode vs Order Count](https://github.com/Anshpatel1825/ecommerce-sales-analysis/blob/main/Screenshot%202025-06-20%20125349.png?raw=true)
  ### Insight:
- Standard Class dominates (~6000 orders), preferred due to cost or balance of speed.
- Same Day Delivery (~600 orders) is least used, likely due to higher cost or limited availability.

## 2>State-wise Sales Distribution
- Purpose: Identify top-performing states by sales volume.
  ![State-wise Sales Distribution](https://github.com/Anshpatel1825/ecommerce-sales-analysis/blob/main/Screenshot%202025-06-20%20125409.png?raw=true)

### Insight:
- California, New York, and Texas are top revenue states (~₹2M total).
- Low-sales states like Wyoming and West Virginia present growth opportunities.

## 3>Delivery Time Analysis
- Purpose: Analyze how quickly orders are delivered.
  ![Delivery Time Analysis](https://github.com/Anshpatel1825/ecommerce-sales-analysis/blob/main/Screenshot%202025-06-20%20125420.png?raw=true)

### Insight:
- Majority of deliveries happen in 4–5 days (~2800 orders).
- Same-day and 1–2 day deliveries are rare, likely premium/niche services.

# 2> Bivariate Analysis

## 4>Sales by Category
- Purpose: See which product categories drive sales.
  ![Sales by Category](https://github.com/Anshpatel1825/ecommerce-sales-analysis/blob/main/Screenshot%202025-06-20%20125432.png?raw=true)

### Insight:
- Technology category leads (~₹850k revenue).
- Furniture and Office Supplies contribute steadily (~₹730k).

## 5>Profit by Sub-Category
- Purpose: Identify the most and least profitable sub-categories.
  ![Profit by Sub-Category](https://github.com/Anshpatel1825/ecommerce-sales-analysis/blob/main/Screenshot%202025-06-20%20125442.png?raw=true)

### Insight:
- Copiers and Phones top profit contributors.
- Tables and Bookcases generate consistent losses.

## 6>Profit by Segment
- Purpose: Compare profit across customer segments.
  ![Profit by Segment](https://github.com/Anshpatel1825/ecommerce-sales-analysis/blob/main/Screenshot%202025-06-20%20125502.png?raw=true)

### Insight:
- Consumer segment delivers highest profit (~₹135k).
- Home Office segment is least profitable (~₹60k).


## 7>Sales by Region
- Purpose:  Identify sales distribution across regions.
  ![Sales by Region](https://github.com/Anshpatel1825/ecommerce-sales-analysis/blob/main/Screenshot%202025-06-20%20125511.png?raw=true)

### Insight:
- West and East regions dominate sales (~₹725k and ₹680k).
- South region lags (~₹395k).

# 3.Multivariate Analysis
## 8> Profit vs Sub-Category Heatmap
- Purpose:Visualize regional profitability by sub-category.
  ![Profit vs Sub-Category Heatmap](https://github.com/Anshpatel1825/ecommerce-sales-analysis/blob/main/Screenshot%202025-06-20%20125539.png?raw=true)

### Insight:
- Accessories & Phones are profitable across all regions.
- Tables & Bookcases show losses, especially in East & South.
- East region is the most profitable across sub-categories.

## 9> Discount vs Sales vs Profit Ratio
- Purpose: Analyze how discounts impact sales and profit margins.
  ![Discount vs Sales vs Profit Ratio](https://github.com/Anshpatel1825/ecommerce-sales-analysis/blob/main/Screenshot%202025-06-20%20125547.png?raw=true)

### Insight:
- 0% discount products had highest sales + profit (especially Technology).
- Deep discounts (>60%) didn’t drive sales and hurt profit margins.
- Furniture showed mixed performance due to delivery/cost factors.

# Key Takeaways
- Focus on Technology category and Consumer segment for higher returns.
- Avoid deep discounts as they reduce margins without boosting sales.
- Rework pricing/cost structure for Tables and Bookcases.
- Expand in East & West regions; develop strategy for South & Central.
  






