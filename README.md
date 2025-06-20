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
  ![Chart Title](images/filename.png)

### Insight:
- California, New York, and Texas are top revenue states (~₹2M total).
- Low-sales states like Wyoming and West Virginia present growth opportunities.

## 3>Delivery Time Analysis
- Purpose: Analyze how quickly orders are delivered.
  ![Chart Title](images/filename.png)

### Insight:
-Majority of deliveries happen in 4–5 days (~2800 orders).
- Same-day and 1–2 day deliveries are rare, likely premium/niche services.

# 2> Bivariate Analysis

## 4>Sales by Category
- Purpose: See which product categories drive sales.
  ![Chart Title](images/filename.png)

### Insight:
- Technology category leads (~₹850k revenue).
- Furniture and Office Supplies contribute steadily (~₹730k).

## 5> Profit by Sub-Category
- Purpose: Identify the most and least profitable sub-categories.
  ![Chart Title](images/filename.png)

### Insight:
- Copiers and Phones top profit contributors.
- Tables and Bookcases generate consistent losses.

## 6> Profit by Segment
- Purpose: Compare profit across customer segments.
  ![Chart Title](images/filename.png)

### Insight:
- Consumer segment delivers highest profit (~₹135k).
- Home Office segment is least profitable (~₹60k).


## 7>Sales by Region
- Purpose:  Identify sales distribution across regions.
  ![Chart Title](images/filename.png)

### Insight:
- West and East regions dominate sales (~₹725k and ₹680k).
- South region lags (~₹395k).

# 3.Multivariate Analysis
## 8> Profit vs Sub-Category Heatmap
- Purpose:Visualize regional profitability by sub-category.
  ![Chart Title](images/filename.png)

### Insight:
- Accessories & Phones are profitable across all regions.
- Tables & Bookcases show losses, especially in East & South.
- East region is the most profitable across sub-categories.

## 9> Discount vs Sales vs Profit Ratio
- Purpose: Analyze how discounts impact sales and profit margins.
  ![Chart Title](images/filename.png)

### Insight:
- 0% discount products had highest sales + profit (especially Technology).
- Deep discounts (>60%) didn’t drive sales and hurt profit margins.
- Furniture showed mixed performance due to delivery/cost factors.
  






