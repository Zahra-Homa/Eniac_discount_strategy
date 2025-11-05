## Case Study: Eniac's Discount Strategy

This project was completed as part of my Data Analytics Bootcamp at WBS Coding School.
It focuses on analyzing product discount strategies at Eniac, an e-commerce technology company, using Python for data cleaning, visualization, and storytelling.

### Project Overview

The goal of this analysis was to support Eniac's management in resolving an ongoing debate:
Are product discounts beneficial to the company in the long run?

Two opposing perspectives exist within the company:

Marketing Team Lead: Believes that discounts boost customer acquisition, satisfaction, and retention.

Board of Investors: Concerned that discounts reduce total revenue and push the company toward competing on price instead of quality.

My task as a data analyst was to use internal company data to uncover insights and provide data-driven recommendations.

### Tools 

- **Python (Jupyter Notebook)**
- **pandas, seaborn, matplotlib**

### Key Insights 

- **Limited dataset:** Covers only 5 quarters, insufficient to confirm seasonal trends. At least 2 years of data would be needed for robust seasonality analysis.
- **Discounted Products:** 3,498 products were discounted (6.32% of the total).
- **Seasonal demand patterns:**  
  - Sales peak in November and December (Black Friday & Christmas).  
  - Sales dip from January to March (post-holiday slowdown).  
    Suggests revenue is more influenced by seasonal demand than discounts.
- **Revenue vs. Discounts:**  
  - Heavy discount ≠ high revenue: e.g., Apple products were top revenue drivers with low average discounts.  
  - Greater than 1400$ price range had the highest average discount but contributed less to overall revenue after getting discounted.  
  - Mid-range products (100-600) generated strong revenue with moderate discounts (most efficient segment).
- **Category-level trends:**  
  - Top 5 categories (Storage, Monitor, RAM, Tablet, Smartphone): higher discounts showed negative correlation with revenue.  
  - Even if units sold increase, total revenue may decline due to margin erosion.

### Dataset

- **Source:** Provided by WBS Coding School.  
- **Note:** Due to its large size, the dataset cannot be uploaded here.




















