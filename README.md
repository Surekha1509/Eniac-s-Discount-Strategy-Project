Eniac's_discount_Strategy_Project

This project analyzes the discount strategy applied by ENIAC between January 2017 and March 2018. After cleaning the data and classifying the products sold by ENIAC,  Additionally, it explores the relationship between discounts, seasonal shifts, special events, product categories, and various pricing and quantity dynamics.

The worked materials provided by Data Sceince Bootcamp WBS Coding Berlin 

on date : 27-10.2025

Team work by https://github.com/afol and https://github.com/rudrapra084

Final Project PPT : https://docs.google.com/presentation/d/149s6PaCtws4OgAmovATNkznon7Jc5itWTVfBsU-4CaU/edit?usp=drive_link

 Dataset & Sources https://drive.google.com/drive/folders/13OGwxS4tp-HjQRhCtpPfhJDnipnb90dm?usp=sharing

Data description

orders.csv – Every row in this file represents an order.
order_id – a unique identifier for each order
created_date – a timestamp for when the order was created
total_paid – the total amount paid by the customer for this order, in euros state
“Shopping basket” – products have been placed in the shopping basket
“Place Order” – the order has been placed, but is awaiting shipment details
“Pending” – the order is awaiting payment confirmation
“Completed” – the order has been placed and paid, and the transaction is completed.
“Cancelled” – the order has been cancelled and the payment returned to the customer.
orderlines.csv – Every row represents each one of the different products involved in an order.

id – a unique identifier for each row in this file
id_order – corresponds to orders.order_id
product_id – an old identifier for each product, nowadays not in use
product_quantity – how many units of that product were purchased on that order
sku – stock keeping unit: a unique identifier for each product
unit_price – the unitary price (in euros) of each product at the moment of placing that order
date – timestamp for the processing of that product
products.csv

sku – stock keeping unit: a unique identifier for each product
name – product name
desc – product description
price – base price of the product, in euros
promo_price – promotional price, in euros
in_stock – whether or not the product was in stock at the moment of the data extraction
type – a numerical code for product type
brands.csv

short – the 3-character code by which the brand can be identified in the first 3 characters of products.sku
long – brand name

Tools Used:
Python

Libraries: Seaborn , Pandas

Environment: google Colab


Analysis and Key Findings

Higher discounts do not necessarily lead to higher revenue.

Blanket high-rate discount strategies are less effective; strategic, time-limited offers are recommended.

Recommendations

Maintain discounts within a reasonable range to preserve profit margins.

Standardize product categorization and implement duplicate checks for cleaner, more reliable analysis in the future.

The highest revenue comes from products sold with discounts between 15% and 25%

Very high discounts on cheap products do not boost the revenue
