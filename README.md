# Danny's-Diner-SQL-Based-Analysis-of-Customer-Spending-and-Preferences


## Introduction


Danny seriously loves Japanese food so in the beginning of 2021, he decides to embark upon a risky venture and opens up a cute little restaurant that sells his 3 favourite foods: sushi, curry and ramen. The restaurant is facing the challenges that many new establishments encounter. The diner has collected basic operational data over the initial months, but the utilization of this data to make informed business decision remains a problem to them.

The objective of this report is to assist Danny's Diner in navigating through these challenges by leveraging the collected data. By employing SQL-based analysis, this report aims to unearth valuable insights into customer behavior, spending patterns, and menu item preferences. These insights are crucial for making informed decisions to enhance the customer experience, potentially expanding the customer loyalty program, and ultimately ensuring the sustained growth and success of Danny’s Diner


## Problem Statement

Danny wants to use the data to answer a few simple questions about his customers, especially about their visiting patterns, how much money they’ve spent and also which menu items are their favourite. Having this deeper connection with his customers will help him deliver a better and more personalised experience for his loyal customers.

He plans on using these insights to help him decide whether he should expand the existing customer loyalty program - additionally he needs help to generate some basic datasets so his team can easily inspect the data without needing to use SQL.


## Case Study Questions

-- What is the total amount each customer spent at the restaurant?

-- How many days has each customer visited the restaurant?

-- What was the first item from the menu purchased by each customer?

-- What is the most purchased item on the menu and how many times was it purchased by all customers?

-- Which item was the most popular for each customer?

-- Which item was purchased first by the customer after they became a member?

-- Which item was purchased just before the customer became a member?

-- What is the total items and amount spent for each member before they became a member?

-- If each $1 spent equates to 10 points and sushi has a 2x points multiplier - how many points would each customer have?

-- In the first week after a customer joins the program (including their join date) they earn 2x points on all items, not just sushi - how many points do customer A and B have at the end of January?

## Data Source

Danny company provided the data to be used for the analysis to write fully functioning SQL queries to help him answer his questions!
The 3 key datasets for this case study are:

**-- sales**

**-- menu**

**-- members**

## Data Model and Schema
![image](https://github.com/Taofik06/Danny-s-Diner-SQL-Based-Analysis-of-Customer-Spending-and-Preferences/assets/123642327/fad94450-03c1-4c63-8598-208e7c7f46ed)

## Solutions
1. What is the total amount each customer spent at the restaurant?
![image](https://github.com/Taofik06/Danny-s-Diner-SQL-Based-Analysis-of-Customer-Spending-and-Preferences/assets/123642327/8a2f960f-3112-41f9-9d12-737c8b7905b8)

![image](https://github.com/Taofik06/Danny-s-Diner-SQL-Based-Analysis-of-Customer-Spending-and-Preferences/assets/123642327/3d7d8db5-0b34-4b4b-be45-8a04dd4631e7)

The three customers A, B and C have spent $76, $74 and $36 respectively

2. How many days has each customer visited the restaurant?
   ![image](https://github.com/Taofik06/Danny-s-Diner-SQL-Based-Analysis-of-Customer-Spending-and-Preferences/assets/123642327/dcf84375-f0a0-425e-bfb7-8ae39cb3c039)
![image](https://github.com/Taofik06/Danny-s-Diner-SQL-Based-Analysis-of-Customer-Spending-and-Preferences/assets/123642327/5ecba840-5418-41fe-81d4-dd3c17044053)

Customer B has visited the restaurant 6 times which is the most among all customers studied. 

