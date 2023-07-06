# Recommender System for H&M

<img width="260" alt="image" src="https://user-images.githubusercontent.com/97483777/224587623-80d8ce21-43d3-460d-803a-a30cb7d49efb.png">

## Objective:
     - Help customers choose by making a deep-learning neural network model.
     - Improve sustainability, by reducing returns and wastes.
     - Decreased returns mean more cost-cutting for the company too.
              
## Identified Problem:
We are helping H&M by making a deep learning neural network to recommend customers' clothing and accessories on the basis of their purchase
by answering the following business question:

    - Which product is the most popular among customers?
    - What is the average amount people are spending on each transaction?
    - What were the months when people purchased the most?

## Data Description: 
We are dividing the data in the following tables:

1. Article.csv – It gives us insight into the products
   * Article_id: unique id for each product
   * Prod_name: name of the product
   * Product_type_name: type of product(sweater,shirt,pant)

2. Customers.csv – It gives us insight into the customers we have 
   * Customer_id: unique id for each customer
   * Club_member_status: if the customer is an active member or not
   * Age: age of the customer
   * Postal_code: postal code of each customer
   
3. Transaction_train.csv – This gives us insight into the transactions made by customers for the products
   * T_dat: date of transaction
   * Article_id: unique id for each product
   * Customer_id: unique id for each customer
   * Price: amount spent on each transaction





