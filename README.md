# KR Tableau project
# Company Sales & Profit Dashboard (Tableau)

This repository contains a Tableau workbook that investigates where and when our company is encountering profit shortfalls, and which products and regions are underperforming in sales and margins.

---
![image](https://github.com/user-attachments/assets/af3be3d4-3a73-47c8-8c12-32d6952bcbeb)


## Dashboard Overview

1. **Profit Hotspots Map**  
   - A geographic scatterplot of all sales locations in South Korea  
   - Circle size = sales volume; color gradient = profit (orange = loss, blue = high profit)  
   - Quickly pinpoints cities or areas where profit issues are most severe

2. **Product‑Region Profit Analysis**  
   - Bar charts of sales by product sub‑category across major regions (Capital, Yeongnam, Honam, Chungcheong, Gangwon)  
   - Highlights the lowest‑margin products (e.g., “Chairs” in the Capital region)  
   - Side‑by‑side comparison to see which product lines are dragging down profitability in each area

3. **Time Series Profit Trends**  
   - Monthly line chart (2016–2019) of cumulative sales vs. cumulative profit  
   - Reveals when profit gaps first emerged and how they’ve widened over time  
   - Shows seasonal peaks in sales (e.g., year‑end spikes) versus flat or negative profit growth in certain months

---

## Key Takeaways

- **Where are profit issues most acute?**  
  - Regions around Busan and Daejeon exhibit a high concentration of low‑profit or loss‑making locations.  
  - Northern Gangwon shows sporadic but sharp loss events.

- **Which products are under‑profitable?**  
  - In the Capital region, **Chairs** and **Tables** generate strong sales but yield slim margins.  
  - In Yeongnam, **Office Machines** (e.g., Fax/Printers) show negative profitability trends.

- **When did profit shortfalls begin?**  
  - From late 2017 onward, cumulative profit growth lags behind sales growth—especially in Q1 and Q3.  
  - Despite robust holiday sales in December, January profits dip, indicating rising costs or discounting pressures.
 
  # Starbucks Korea Menu & Store Dashboard
This Tableau dashboard combines nutritional analysis of Starbucks products with a geographic overview of store distribution in South Korea.

![image](https://github.com/user-attachments/assets/75c3cf19-06d6-4707-b7ca-42f448d295e5)

1️⃣ Category‑Level Calories & Caffeine
Total calories and total caffeine per category are computed by summing across all menu items.

We then calculate average calories and average caffeine for each category.

A dual‑axis bar chart shows average calories on the left axis and average caffeine on the right.

Only the right‑axis (average caffeine) bars are color‑coded—from light to deep red as caffeine increases.

Finally, categories are sorted in descending order of average calories.

2️⃣ Sugar vs. Calories Correlation
A scatter plot examines the relationship between sugar content (x‑axis) and calories (y‑axis).

Each mark’s size and color encode its caffeine level; opacity is lowered and a border added to improve readability.

This reveals that while higher sugar generally corresponds to higher calories, calorie counts still vary significantly between items with similar sugar levels.


![image](https://github.com/user-attachments/assets/a6b9493f-fe5a-4c12-8936-5eeec05e2177)

3️⃣ Menu‑Level Calories & Caffeine Treemap
Uses a treemap to display every menu item’s calories and caffeine in a hierarchical layout.

Rectangle size reflects calories and color intensity reflects caffeine.

Because Tableau aggregates measures according to the dimensions in view, we visualize each item’s raw calorie and caffeine values (no further averaging).

4️⃣ Combined Category & Menu View
Brings together the “Category‑Level” and “Menu‑Level” sheets into a single consolidated view for side‑by‑side comparison.



![image](https://github.com/user-attachments/assets/c0e066ef-5b21-4ddb-b333-7fc951b383b1)

5️⃣ Store Distribution Map
Maps every Starbucks location in Korea by city/district.

Marker size and color indicate the number of stores (calculated by counting unique store codes).

Highlights which districts have the highest concentration of Starbucks outlets.
