# 🍕 SQL Pizza Sales Analysis  

## 📌 Project Overview  
This project analyzes **pizza sales data** using SQL to uncover business insights, optimize menu offerings, and improve sales performance. The dataset includes order details, pizza types, and sales transactions.  

## 📊 Key Objectives  
- Analyze **total revenue, sales trends, and peak hours**  
- Identify **best-selling and least-selling pizzas**  
- Evaluate **average order value and customer purchasing patterns**  
- Optimize **inventory based on pizza demand**  

## 🛠️ Tools & Technologies  
- **SQL** 
- **Database Management System**  


## 📂 Dataset Information  
The dataset consists of the following tables:  

### 1️⃣ `orders`  
| Column Name  | Data Type | Description |  
|-------------|----------|-------------|  
| order_id    | INT      | Unique order ID |  
| order_date  | DATE     | Date of order |  
| order_time  | TIME     | Time interval |  

### 2️⃣ `order_details`  
|   Column Name       | Data Type    | Description |  
|---------------------|--------------|-------------| 
| order_details_id    | INT          | Order details ID (FK) |
| order_id            | INT          | Order ID (FK) |  
| pizza_id            | VARCHAR(50)  | Pizza ID (FK) |  
| quantity            | INT          | Number of pizzas ordered |  

### 3️⃣ `pizzas`  
| Column Name     |   Data Type     | Description |  
|-----------------|-----------------|-------------|  
| pizza_id        | VARCHAR(50)     | Unique pizza identifier |  
| pizza_type_id   | VARCHAR(50)     | Pizza type (Veg, Non-Veg) |  
| size            | TEXT            | Pizza size |  
| price           | DECIMAL         | Price of pizza |  

### 3️⃣ `pizzas_types`  
| Column Name     |   Data Type     | Description |  
|-----------------|-----------------|-------------|  
| pizza_type_id   | VARCHAR(50)     | Pizza type (Veg, Non-Veg) |   
| name            | TEXT            | Name of the pizza |  
| category        | TEXT            | Pizza category type  |  
| ingredients     | VARCHAR(255)    | Pizza ingredients |  



