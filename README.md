# Recommendor System for H&M

## Objective:
     - Help customers make the right choice by making deep learning neural network model.
     - Improve sustainability, by reducing returns and wastes.
     - Decreased returns means more cost cutting for company too.
              
## Identified Problem:
We are helping H&M by making a deep learning neural network to recommend customers clothing and accessories on the basis of their purchase
by answering the following business question:

    - Which product is the most popular within customers?
    - What is the average amount people are spending on each transaction?
    - What were the months when people purchased the most?

## Data Description: 
We are dividing the data in the following tables:

1. Article.csv – It gives us the insight on the products
   * Article_id: unique id for each product
   * Prod_name: name of the product
   * Product_type_name: type of product(sweater,shirt,pant)

2. Customers.csv – It gives us the insight about the customers we have 
   * Customer_id: unique id for each customer
   * Club_member_status: if customer is an active member or not
   * Age : age of the customer
   * Postal_code: postal code of each customers
   
3. Transaction_train.csv – This gives us the insight about the transactions made by customers for the products
   * T_dat : date of transaction
   * Article_id: unique id for each product
   * Customer_id: unique id for each customer
   * Price: amount spent on each transaction





