# E-commerce segmentation and recommender system

## CSCA 5632 Unsupervised Algorithms in Machine Learning Final Project

Nicolas Veas

## Introduction

Understanding the audience of an ecommerce platform is crucial for effective marketing, as it enables the use of personalized strategies. Developing a customer segmentation model allows us to understand the different profiles and preferences of the ecommerce customers. This enhances customer engagement and also supports the implementation of a recommender system that could help improving the shopping experience by providing personalized product suggestions that a certain customer will be likely to purchase.

In this project, I'll use unsupervised learning model to segment customers and build a recommender system.

The data used is from kaggle from the following link:

https://www.kaggle.com/datasets/shrishtimanja/ecommerce-dataset-for-data-analysis

## Data

-  The data set consists of 14 features and 55000 entires of customer transactions.

## Objective

-  To segment customers into distinct groups
-  To build a recommender system that recommend products to customers

## Data Dictionary

-  CID (Customer ID): A unique identifier for each customer.
-  TID (Transaction ID): A unique identifier for each transaction.
-  Gender: The gender of the customer, categorized as Male or Female.
-  Age Group: Age group of the customer, divided into several ranges.
-  Purchase Date: The timestamp of when the transaction took place.
-  Product Category: The category of the product purchased, such as Electronics, Apparel, etc.
-  Discount Availed: Indicates whether the customer availed any discount (Yes/No).
-  Discount Name: Name of the discount applied (e.g., FESTIVE50).
-  Discount Amount (INR): The amount of discount availed by the customer.
-  Gross Amount: The total amount before applying any discount.
-  Net Amount: The final amount after applying the discount.
-  Purchase Method: The payment method used (e.g., Credit Card, Debit Card, etc.).
-  Location: The city where the purchase took place.
