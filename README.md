# Pizza Sales Analysis – 2015

## Executive Summary

This report provides a comprehensive overview of pizza sales across a full year, from January 1 to December 31, 2015. Using interactive dashboards in Power BI, I explored total revenue, order trends, customer preferences, and product performance. 

The analysis revealed:
- Over **$817K** in revenue generated from **21,350 orders** and nearly **50,000 pizzas sold**
- Strong customer preference for **Classic** and **Large** pizzas
- Clear patterns in **weekly and monthly sales trends**, with a noticeable dip in **October**
- High-performing products like the **Classic Deluxe** and **Thai Chicken** pizzas
- Opportunities to improve performance through targeted promotions and smarter product positioning

These insights can help guide strategic planning in marketing, inventory, staffing, and product bundling.

---

## Objective

The main goal of this project was to evaluate the performance of a pizza business throughout 2015. I used Power BI to analyze key business metrics, such as revenue, total orders, pizza preferences by size and category, and variations in customer behavior by day and month.

The insights generated from this project are designed to support data-driven decisions in areas such as **menu strategy**, **promotional planning**, **seasonal adjustments**, and **operational efficiency**.

---

## Data Overview

The analysis is based on a transactional dataset containing **48,620 records**, where each row represents a pizza sold. 

You can access the source dataset here:  
[**Pizza Sales Dataset (Google Sheets)**](https://docs.google.com/spreadsheets/d/1mF1G56ZrwQlksmS5meWgC1yXRgeqGV2T/edit?gid=679792667#gid=679792667)

### Key fields in the dataset:
- `pizza_id`, `order_id`: Unique identifiers for each pizza and order
- `pizza_name_id`: Grouped product code for each pizza
- `order_datetime`: Date and time of the order
- `unit_price`, `total_price`: Price information per pizza and per line item
- `pizza_size`, `pizza_category`: For analyzing sales by product segmentation
- `pizza_ingredients`, `pizza_name`: Descriptive data for product-level insights

## Key Findings

### 1. Customer Preferences
- **Classic pizzas** were the top-selling category, with over **15,000 units sold**
- **Large size** dominated, representing **45.89%** of all pizzas sold
- The **least popular size** was XX-Large, with minimal contribution to overall volume

![Sales by Category](https://github.com/IrinaOrias/Pizza-by-the-Numbers-A-12-Month-Review/blob/main/Imagenes/Sales_by%20_Category.PNG?raw=true)  
![Sales by Size](https://github.com/IrinaOrias/Pizza-by-the-Numbers-A-12-Month-Review/blob/main/Imagenes/Sales_by%20_Size.PNG?raw=true)

---

### 2. Best and Worst Sellers
- **Top pizza by revenue**: *The Thai Chicken Pizza*
- **Top pizza by quantity and orders**: *The Classic Deluxe Pizza*
- **Lowest performers**: *The Brie Carre Pizza* ranked lowest across revenue, quantity, and order count

![Best and Worst Sellers](https://github.com/IrinaOrias/Pizza-by-the-Numbers-A-12-Month-Review/blob/main/Imagenes/Best%20and%20worst%20sellers.PNG?raw=true)

---

### 3. Daily and Weekly Patterns
- Sales peaked on **Friday**, with approximately **3.5K orders**
- **Sunday** had the lowest average daily orders
- Weekends (especially Friday and Saturday evenings) were the busiest times

![Weekly Trends](https://github.com/IrinaOrias/Pizza-by-the-Numbers-A-12-Month-Review/blob/main/Imagenes/Weekly%20Trends.PNG?raw=true)

---

### 4. Monthly Trends
- **July** was the best-performing month with **1,935 orders**
- **October** had the lowest order volume, with **1,640 orders**
- There was a noticeable decline in orders between **August and October**

![Monthly Trends](https://github.com/IrinaOrias/Pizza-by-the-Numbers-A-12-Month-Review/blob/main/Imagenes/Montly%20thrend.PNG?raw=true)

---

## Recommendations and Action Points

### 1. Drive Sales in Low-Performing Months

**Observation:** October was the weakest month of the year.

**Recommendation:**  
- Run promotions or limited-time offers in the fall to boost interest and engagement  
- Use themed campaigns tied to local events or holidays to drive urgency


---

### 2. Promote Bestsellers for Higher Value

**Observation:** Classic pizzas and larger sizes perform consistently well.

**Recommendation:**  
- Create combo meals featuring bestsellers like the Classic Deluxe Pizza and Large size  
- Add upsell prompts at checkout for size upgrades or premium toppings


---

### 3. Capitalize on Busy Days

**Observation:** Fridays and Saturdays are peak times for orders.

**Recommendation:**  
- Launch premium bundle deals or family meals specifically for weekends  
- Reinforce staff schedules and delivery capacity to handle volume spikes



