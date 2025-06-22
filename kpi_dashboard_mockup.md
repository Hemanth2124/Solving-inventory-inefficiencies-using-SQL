# Inventory KPI Dashboard/Report Mock-up

## Executive Summary
This report provides a mock-up of an Inventory Key Performance Indicator (KPI) Dashboard designed for Urban Retail Co. The dashboard aims to offer actionable insights into inventory management, helping to reduce stockouts and overstocks, improve supply chain efficiency, and enhance profitability. The KPIs presented are derived from the SQL queries and analytical scripts developed in this project.

## Key Performance Indicators (KPIs)

### 1. Stock Level Overview

**Purpose:** To provide a real-time view of inventory levels across all stores and warehouses.

**Visual Representation:**
*   **Total Inventory Value:** A large number displaying the total monetary value of all inventory.
*   **Inventory by Category:** A bar chart showing the distribution of inventory value across different product categories (e.g., Electronics, Clothing, Toys).
*   **Inventory by Store/Warehouse:** A map or bar chart indicating inventory levels at each location.

**Mock-up Data/Insights:**
*   **Total Inventory Value:** $1,500,000
*   **Top 3 Categories by Inventory Value:**
    *   Electronics: $500,000
    *   Clothing: $400,000
    *   Home Essentials: $300,000
*   **Store S001 (West Region):** Current Inventory Level: 15,000 units
*   **Warehouse W001 (East Region):** Current Inventory Level: 50,000 units

### 2. Low Inventory Alerts & Reorder Recommendations

**Purpose:** To proactively identify products nearing stockout and suggest reorder quantities.

**Visual Representation:**
*   **Alerts Table:** A table listing products below their reorder point, showing `Product ID`, `Category`, `Current Stock`, `Reorder Point`, and `Recommended Order Quantity`.
*   **Reorder Point Trend:** A line graph showing historical reorder points vs. actual inventory levels for critical products.

**Mock-up Data/Insights:**
*   **Alerts:**
| Product ID | Category | Current Stock | Reorder Point | Recommended Order Quantity |
|------------|----------|---------------|---------------|----------------------------|
| P0016      | Clothing | 45            | 50            | 100                        |
| P0096      | Toys     | 30            | 40            | 80                         |
| P0031      | Electronics | 20            | 25            | 50                         |

*   **Reorder Point Estimation (Example for P0016):** Based on average daily sales of 7 units and a 7-day lead time, the estimated reorder point is 49 units (7 units/day * 7 days). Adding a safety stock of 50% of lead time sales (24.5 units) brings the reorder point to approximately 74 units.

### 3. Inventory Turnover Analysis

**Purpose:** To assess how efficiently inventory is being sold and replaced.

**Visual Representation:**
*   **Inventory Turnover Ratio by Product:** A bar chart or table showing turnover ratios for top/bottom products.
*   **Fast-Moving vs. Slow-Moving Products:** A scatter plot or quadrant chart categorizing products based on sales volume and turnover.

**Mock-up Data/Insights:**
*   **Top 3 Products by Turnover Ratio:**
    *   P0016 (Clothing): 12.5 (High turnover, fast-selling)
    *   P0096 (Toys): 9.8
    *   P0031 (Electronics): 7.2
*   **Bottom 3 Products by Turnover Ratio:**
    *   PXXX (Home Essentials): 1.2 (Low turnover, slow-moving)
    *   PYYY (Personal Care): 0.9
    *   PZZZ (Electronics): 0.7

### 4. Stockout Rate and Inventory Age

**Purpose:** To monitor the frequency of stockouts and the age of inventory.

**Visual Representation:**
*   **Stockout Rate by Product/Category:** A bar chart highlighting products or categories with high stockout rates.
*   **Average Inventory Age:** A gauge or bar chart showing the average age of inventory across the entire stock or by category.

**Mock-up Data/Insights:**
*   **Highest Stockout Rates:**
    *   P0016 (Clothing): 5% (meaning 5% of the time, this product was out of stock)
    *   P0096 (Toys): 3%
*   **Average Inventory Age (Estimated Days of Supply):**
    *   Overall: 60 days
    *   Electronics: 75 days (Higher, indicating potential overstock or slower sales)
    *   Clothing: 45 days (Lower, indicating faster movement)

### 5. Demand Forecasting Trends

**Purpose:** To visualize historical demand patterns and future demand forecasts.

**Visual Representation:**
*   **Historical Sales & Forecast:** A line graph showing past sales data with an overlay of forecasted demand.
*   **Seasonality Component:** A separate chart showing the seasonal component extracted from demand decomposition.

**Mock-up Data/Insights:**
*   **Overall Daily Sales Trend:** Shows a clear upward trend with weekly seasonality (peaks on weekends).
*   **Forecasted Daily Demand (Next 7 Days):** Approximately 150 units/day (based on moving average).

## Recommendations for Business Impact

Based on these KPIs, Urban Retail Co. can:
*   **Optimize Stock Levels:** Use low inventory alerts and reorder recommendations to prevent stockouts of fast-moving items and reduce overstocking of slow-moving items.
*   **Improve Supply Chain Efficiency:** Analyze supplier performance inconsistencies to address issues with order fulfillment and delivery times.
*   **Enhance Customer Satisfaction:** By reducing stockouts, customers will more consistently find desired products, leading to improved satisfaction.
*   **Boost Profitability:** Reduced holding costs from optimized inventory and increased sales from fewer stockouts directly contribute to higher profitability.

## Conclusion
This dashboard mock-up demonstrates how data-driven insights can transform Urban Retail Co."s inventory management. By continuously monitoring these KPIs and acting on the recommendations, the company can achieve significant operational efficiencies and financial benefits.

