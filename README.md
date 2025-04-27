# KR Tableau project
# Company Sales & Profit Dashboard (Tableau)

This repository contains KR Tableau Bootcamp Dashboards: Profit shortfalls, Starbucks Korea metrics, calories & caffeine treemap, category vs menu view, monthly PM₂.₅ trends, and Big Mac Index comparison.

[Dashboard link on Tableau Public](https://public.tableau.com/app/profile/jiyoon.shin1127/viz/_17452201366720/1?publish=yes)
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

 ---
 
  # Starbucks Korea Menu & Store Dashboard
This Tableau dashboard combines nutritional analysis of Starbucks products with a geographic overview of store distribution in South Korea.


[Dashboard link](https://public.tableau.com/app/profile/jiyoon.shin1127/viz/_17457506575110/sheet2?publish=yes)
![image](https://github.com/user-attachments/assets/9c25e155-2018-4a9d-85d7-2d16f26a3682)



[Dashboard link on Tableau Public](https://public.tableau.com/app/profile/jiyoon.shin1127/viz/StarbucksCategoryNutritionDashboardAverageCaloriesCaffeinewithSugarCalorieComparison/sheet4?publish=yes)
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



[Dashboard link on Tableau Public](https://public.tableau.com/app/profile/jiyoon.shin1127/viz/StarbucksMenuDashboardCaloriesCaffeinebyItem/sheet1?publish=yes)
![image](https://github.com/user-attachments/assets/a6b9493f-fe5a-4c12-8936-5eeec05e2177)

3️⃣ Menu‑Level Calories & Caffeine Treemap
Uses a treemap to display every menu item’s calories and caffeine in a hierarchical layout.

Rectangle size reflects calories and color intensity reflects caffeine.

Because Tableau aggregates measures according to the dimensions in view, we visualize each item’s raw calorie and caffeine values (no further averaging).

4️⃣ Combined Category & Menu View
Brings together the “Category‑Level” and “Menu‑Level” sheets into a single consolidated view for side‑by‑side comparison.



[Dashboard link on Tableau Public](https://public.tableau.com/app/profile/jiyoon.shin1127/viz/StarbucksinSouthKorea/sheet3?publish=yes)
![image](https://github.com/user-attachments/assets/c0e066ef-5b21-4ddb-b333-7fc951b383b1)

5️⃣ Store Distribution Map
Maps every Starbucks location in Korea by city/district.

Marker size and color indicate the number of stores (calculated by counting unique store codes).

Highlights which districts have the highest concentration of Starbucks outlets.



![image](https://github.com/user-attachments/assets/61b0d687-c75a-43f5-a136-02c64ff3c769)

6️⃣ Compare menus by calorie content – use marker size to encode calories (larger markers for higher‑calorie items).





![image](https://github.com/user-attachments/assets/cede3d72-7a42-46ac-8284-0203b53b89c7)

7️⃣ Box plot of total calories per menu within each category – display the distribution of summed calories at the menu level.




![image](https://github.com/user-attachments/assets/799060a7-9cfa-40e6-a326-70697babe932)

8️⃣ Menu‑level comparison of caffeine content against an 80 mg threshold – classify each item as above or below 80 mg.




[Dashboard link on Tableau Public](https://public.tableau.com/app/profile/jiyoon.shin1127/viz/_17457549508380/sheet0?publish=yes)
![image](https://github.com/user-attachments/assets/58d6049f-0b79-46f7-b157-3b96a72a56a5)


[Dashboard link on Tableau Public](https://public.tableau.com/app/profile/jiyoon.shin1127/viz/_17457552696150/4?publish=yes)
![image](https://github.com/user-attachments/assets/98e54ba7-7c7f-4554-9b17-e46b2ef39941)






[Dashboard link on Tableau Public](https://public.tableau.com/app/profile/jiyoon.shin1127/viz/BigMacPriceComparisonbyCountry/sheet1?publish=yes)
![image](https://github.com/user-attachments/assets/fe9fb346-8888-4611-add0-e79334eff561)



[Dashboard link on Tableau Public](https://public.tableau.com/app/profile/jiyoon.shin1127/viz/YearlyMinimumandMaximumPriceDifferences/sheet2?publish=yes)
![image](https://github.com/user-attachments/assets/f331e876-e7e2-4328-9991-c57c4a33e53d)




