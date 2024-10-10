# Coffee Sales Dashboard

This project provides a detailed overview of the Coffee Sales Dashboard, featuring sales and customer insights. The dashboard includes visualizations for total sales, sales by country, and top 5 customers. The data is sourced from the following datasets: `orders`, `customers`, and `products`.

## Datasets Overview

### Orders
The `orders` dataset contains transaction details including order ID, customer details, and product information. Key additions:
- **Sales**: Calculated as `Unit Price * Quantity`
- **Coffee Type Name** and **Roast Type Name** added based on product
- **Loyalty Card**: Indicates if the customer has a loyalty card

### Customers
The `customers` dataset provides details on each customer, including name, email, phone number, and loyalty card membership.

### Products
The `products` dataset lists the available coffee products, with information on coffee type, roast type, unit price, and profit.

## Key Dashboard Insights

[Dashboard](image.png)

### 1. Total Sales
Total sales are calculated based on the `orders` dataset, summing the **Sales** column.

### 2. Sales by Country
The sales data is broken down by country, showing which countries contribute the most to total sales.

### 3. Top 5 Customers
This chart highlights the top 5 customers by purchase volume, calculated from the `orders` data.

## Project Files
- **orders**: The dataset with transactional information, sales calculation, and additional coffee product details.
- **customers**: A list of customers and their contact information.
- **products**: A dataset of coffee types, roast types, prices, and profits.
