# FoodHub Data Analysis (Enhanced Version)

This project is a refined and expanded version of the original analysis completed by **Luciano Lovera** on **September 10, 2022**, as part of the **Postgraduate Program in Data Science and Business Analytics** from the **University of Texas**. The project has been enhanced and restructured to be a professional showcase of applied data analysis, now included in this GitHub portfolio.

---

## 🧠 Project Objective

The purpose of this analysis is to explore and extract key insights from the FoodHub dataset, which contains customer order information including cuisine types, order costs, delivery times, preparation times, and customer ratings. The analysis aims to uncover trends, inefficiencies, and actionable recommendations that could improve overall performance and customer satisfaction.

---

## 📂 Dataset Overview

The dataset consists of 1,898 food delivery orders with the following key columns:
- `order_id`, `customer_id`, `restaurant_name`
- `cuisine_type`, `cost_of_the_order`
- `day_of_the_week`, `rating`
- `food_preparation_time`, `delivery_time`

---

## 🔍 Key Exploratory Sections

### ✅ Order and Customer Insights
- Unique orders, restaurants, and cuisine types analyzed.
- Identification of most ordered cuisines and top-performing restaurants.

### ✅ Cost & Time Distributions
- Histograms and boxplots to understand order costs and delivery time variability.
- Proportion of high-cost orders visualized with thresholds.

### ✅ Ratings and Customer Satisfaction
- Relationship between food preparation/delivery time and customer ratings.
- Distribution of feedback scores and missing ratings.

### ✅ Weekday vs Weekend Dynamics
- Comparison of order frequency and delivery performance by day type.
- Popular cuisines on weekends and associated delivery behaviors.

### ✅ Revenue & Business Insights
- Calculation of total revenue based on commission brackets.
- High-value customers and restaurant qualification for promotions.

---

## 📊 Data Visualizations

All visualizations are built using `matplotlib` and `seaborn`. Key plots include:

- Cost and delivery time distributions  
- Boxplots grouped by cuisine type and rating  
- Correlation matrix and pairplots  
- Bar plots for weekend cuisines, top restaurants, and price categories  
- Annotated mean values and threshold lines on relevant charts  

---

## 💡 Insights and Recommendations

📌 **Customer Spending Behavior**
- 29.2% of orders exceed $20 — a strong opportunity to increase revenue through premium promotions and bundle deals.

📌 **Delivery Efficiency**
- Mean delivery time is lower on weekends, suggesting better traffic/logistics. Efforts can be made to replicate this performance during weekdays.

📌 **Cuisine Preferences**
- American, Japanese, and Italian dominate in order volume.
- Spanish, Thai, and Indian cuisines received the highest ratings despite lower order counts — a promotional opportunity.

📌 **Customer Ratings & Time**
- Lower ratings are loosely associated with longer delivery times — optimizing delivery is key to satisfaction.

📌 **Strategic Promotions**
- Identify restaurants with good ratings and frequent customers to allocate discounts and vouchers efficiently.

---

## 📌 Final Conclusions

The FoodHub analysis uncovers important patterns in customer behavior, delivery operations, and cuisine preferences. The insights enable data-driven strategies to:
- Optimize restaurant listings and recommendations.
- Improve delivery logistics.
- Introduce targeted promotions.
- Enhance customer satisfaction through faster service and better communication.

---

## 🛠️ Tools Used
- Python (`pandas`, `numpy`)
- Visualization (`matplotlib`, `seaborn`)
- Jupyter Notebook (VS Code)

---

## 📁 File Structure

