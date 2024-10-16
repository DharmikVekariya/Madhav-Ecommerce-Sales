# Madhav Ecommerce Sales Analysis

This project is a Power BI dashboard designed to analyze sales data for Madhav Ecommerce. The analysis covers key metrics such as profit, sales amount, quantity, and customer behavior across various dimensions like product categories and regions.

![Dashboard Screenshot](./Madhav%20Ecommerce%20Sales.jpg)

## Data Overview

### Tables

1. **Details Table**
   - `order_id`: Unique identifier for each order
   - `amount`: Total sales amount of the order
   - `profit`: Profit generated from the order
   - `quantity`: Quantity of items sold
   - `category`: Main product category
   - `sub_category`: Product sub-category
   - `payment_mode`: Payment method used by the customer (e.g., Credit Card, PayPal)

2. **Orders Table**
   - `order_id`: Unique identifier for each order
   - `order_date`: Date the order was placed
   - `customer`: Customer name or ID
   - `state`: State where the order was delivered
   - `city`: City where the order was delivered

## Dashboard Visualizations

1. **Profit by Month (Stacked Column Chart)**:
   - Displays the monthly profit trends to analyze performance over time.

2. **Sum of Profit by Sub-Category (Stacked Bar Chart)**:
   - Highlights which sub-categories contribute the most to overall profit.

3. **Sum of Quantity by Category (Donut Chart)**:
   - Visualizes the distribution of sold quantities across different product categories.

4. **Sum of Quantity by Payment Mode (Donut Chart)**:
   - Shows customer preferences based on the payment method used.

5. **Sum of Amount by State (Stacked Bar Chart)**:
   - Compares total sales amounts across different states.

6. **Sum of Amount by Customer Name (Stacked Column Chart)**:
   - Identifies the top customers contributing to sales by displaying sales amounts per customer.

7. **Cards**:
   - Summarize key metrics:
     - Total Sales Amount
     - Total Profit
     - Total Quantity Sold
     - Total Advertisement Expenses (if applicable)

8. **Slicers**:
   - **Quarter Slicer**: Filter data by specific quarters.
   - **State Slicer**: Filter data by state.


