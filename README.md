# Target Brazil Orders Dataset

## Overview

Target is a globally recognized brand and a leading retailer in the United States, known for offering exceptional value, inspiration, innovation, and a unique shopping experience. This dataset focuses on Target's operations in Brazil, covering 100,000 orders placed between 2016 and 2018. It includes detailed information on order status, pricing, payment and shipping performance, customer locations, product attributes, and customer reviews.

## Dataset Description

The dataset is available in 8 CSV files, each containing specific information related to Target's operations in Brazil.

### customers.csv

- **customer_id**: ID of the consumer who made the purchase
- **customer_unique_id**: Unique ID of the consumer
- **customer_zip_code_prefix**: Zip Code of consumer’s location
- **customer_city**: Name of the City from where the order is made
- **customer_state**: State Code from where the order is made (e.g., São Paulo - SP)

### sellers.csv

- **seller_id**: Unique ID of the seller registered
- **seller_zip_code_prefix**: Zip Code of the seller’s location
- **seller_city**: Name of the City of the seller
- **seller_state**: State Code

### order_items.csv

- **order_id**: A Unique ID of the order made by the consumers
- **order_item_id**: A Unique ID given to each item ordered in the order
- **product_id**: A Unique ID given to each product available on the site
- **seller_id**: Unique ID of the seller registered in Target
- **shipping_limit_date**: The date before which the ordered product must be shipped
- **price**: Actual price of the products ordered
- **freight_value**: Price rate at which a product is delivered from one point to another

### geolocation.csv

- **geolocation_zip_code_prefix**: First 5 digits of Zip Code
- **geolocation_lat**: Latitude
- **geolocation_lng**: Longitude
- **geolocation_city**: City
- **geolocation_state**: State

### payments.csv

- **order_id**: A Unique ID of the order made by the consumers
- **payment_sequential**: Sequences of the payments made in case of EMI
- **payment_type**: Mode of payment used (e.g., Credit Card)
- **payment_installments**: Number of installments in case of EMI purchase
- **payment_value**: Total amount paid for the purchase order

### orders.csv

- **order_id**: A Unique ID of the order made by the consumers
- **customer_id**: ID of the consumer who made the purchase
- **order_status**: Status of the order made, i.e., delivered, shipped, etc.
- **order_purchase_timestamp**: Timestamp of the purchase
- **order_delivered_carrier_date**: Delivery date at which the carrier made the delivery
- **order_delivered_customer_date**: Date at which the customer received the product
- **order_estimated_delivery_date**: Estimated delivery date of the products

### products.csv

- **product_id**: A Unique identifier for the proposed project
- **product_category_name**: Name of the product category
- **product_name_length**: Length of the string which specifies the name given to the products ordered
- **product_description_length**: Length of the description written for each product ordered on the site
- **product_photos_qty**: Number of photos of each product ordered available on the shopping portal
- **product_weight_g**: Weight of the products ordered in grams
- **product_length_cm**: Length of the products ordered in centimeters
- **product_height_cm**: Height of the products ordered in centimeters
- **product_width_cm**: Width of the product ordered in centimeters

## Potential Use Cases

Analyzing this dataset offers valuable insights into Target's Brazilian operations, revealing details about order processing, pricing strategies, payment and shipping efficiency, customer demographics, product characteristics, and customer satisfaction. This comprehensive dataset is a valuable resource for understanding various business aspects and enhancing strategic decision-making.

## How to Use

1. **Exploratory Data Analysis (EDA)**: Analyze the distribution of customers, orders, and products.
2. **Sales Analysis**: Identify trends in sales over time and across different categories.
3. **Customer Segmentation**: Segment customers based on demographics and purchasing behavior.
4. **Product Performance**: Evaluate product performance based on sales, pricing, and customer reviews.
5. **Shipping and Delivery**: Analyze shipping and delivery performance to identify areas for improvement.
6. **Payment Analysis**: Investigate payment methods and their impact on sales and customer satisfaction.

## Conclusion

This dataset provides a rich source of information for analyzing various aspects of Target's operations in Brazil. It can be used to gain insights into customer behavior, product performance, and operational efficiency, which can ultimately help in making informed business decisions and improving overall performance.


