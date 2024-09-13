# FoodHub Data Analysis: Enhancing Restaurant Demand Insights

This repository contains a case study focused on analyzing customer food order data from **FoodHub**, an online food delivery service. The analysis aims to provide insights into restaurant demand patterns, helping the company enhance customer experience and optimize its business operations.

---

## Context

As New York experiences a rise in the number of restaurants, many students and busy professionals depend on online food delivery services due to their hectic schedules. **FoodHub**, a food aggregator company, allows customers to place online orders from various restaurants through its mobile app. 

FoodHub's app facilitates the entire food delivery process:
- Customers place orders with their chosen restaurants.
- Delivery personnel pick up the food from the restaurant and deliver it to the customer.
- Customers can rate their experience, and FoodHub earns a fixed margin from each order.

Given the growing competition, the company seeks to understand restaurant demand trends to improve customer satisfaction and business performance.

---

## Objective

The goal of this project is to analyze the food order data collected by FoodHub. The analysis will help answer critical business questions to improve customer experience and optimize restaurant partnerships.

---

## Key Questions

1. **Restaurant Popularity**:
   - Which restaurants are receiving the highest number of orders?
   - Are there specific **cuisine types** that are more popular than others?

2. **Order Trends**:
   - How does demand fluctuate across **weekdays and weekends**?
   - Does the day of the week affect the **average order cost**?

3. **Customer Satisfaction**:
   - What is the relationship between **order cost** and **customer rating**?
   - How does **food preparation time** impact customer ratings?

4. **Delivery Performance**:
   - What is the average **delivery time** across different restaurants?
   - Are there any notable patterns in delivery times based on the **day of the week** or **food preparation time**?

---

## Data Description

The dataset consists of details about individual food orders made by customers. Below is the data dictionary for reference:

| Column Name           | Description                                                                                                      |
|-----------------------|------------------------------------------------------------------------------------------------------------------|
| `order_id`            | Unique identifier for each order                                                                                 |
| `customer_id`         | Unique identifier for each customer who placed an order                                                          |
| `restaurant_name`     | Name of the restaurant from which the order was placed                                                           |
| `cuisine_type`        | Type of cuisine ordered by the customer                                                                          |
| `cost`                | Total cost of the order                                                                                          |
| `day_of_the_week`     | Indicates whether the order was placed on a **weekday** (Mon-Fri) or **weekend** (Sat-Sun)                       |
| `rating`              | Customer rating of the order, ranging from 1 to 5                                                                |
| `food_preparation_time` | Time (in minutes) taken by the restaurant to prepare the food, calculated from order confirmation to pick-up     |
| `delivery_time`       | Time (in minutes) taken by the delivery person to deliver the food from pick-up to customer drop-off              |

---

## Project Workflow

1. **Data Exploration**:
   - Perform **univariate** analysis to understand the distribution of individual variables such as **cost**, **rating**, and **delivery time**.
   - Conduct **bivariate** analysis to explore relationships between variables (e.g., **cost vs rating**, **preparation time vs delivery time**).

2. **Demand Analysis**:
   - Analyze **restaurant demand** based on order counts.
   - Identify trends in **cuisine popularity** and **order timings** (weekday vs weekend).

3. **Customer Experience Insights**:
   - Explore factors affecting **customer satisfaction**, such as **order cost**, **preparation time**, and **delivery time**.
   - Identify potential improvements for reducing delivery times and improving ratings.

4. **Visualization**:
   - Create visualizations (e.g., bar charts, heatmaps) to illustrate key findings and patterns in the data.

---

## Files in This Repository

- `foodhub_order.csv`: The dataset containing food order details.
- `README.md`: Project documentation (this file).
- `FDS_Project_LearnerNotebook_FullCode`: Jupyter notebook containing the code for data analysis and visualization.

---

## Conclusion

This analysis provides a comprehensive look at restaurant demand patterns, customer satisfaction, and delivery performance on FoodHub. By addressing the key questions, FoodHub can better understand which restaurants and cuisines are most popular, identify opportunities for operational improvements, and enhance the overall customer experience.

---

## Author

[Sourena Mohit Tabatabaie]  
[MIT Applied Data Science Program]  

---

## License

This project is licensed under the [MIT License](LICENSE).

---

### How to Use This Repository

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Sourena-Mohit/FoodHub-Data-Analysis-Enhancing-Restaurant-Demand-Insights
