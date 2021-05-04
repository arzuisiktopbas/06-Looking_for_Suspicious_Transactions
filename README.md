# HW6 - Looking for Suspicious Transactions
 *by Arzu ISIK TOPBAS*

![image source](https://www.cbc.ca/gfx/images/news/topstories/2013/05/08/hi-bc0130508-fraud-generic-istock.jpg)

[image source:cbc.ca](https://www.cbc.ca/gfx/images/news/topstories/2013/05/08/hi-bc0130508-fraud-generic-istock.jpg)

In this homework activity, I was tasked with building a prototype dashboard.The goal of this dashboard is to provide charts, maps, and interactive visualizations that help customers explore the data and determine if they want to invest in rental properties in San Francisco.

In this homework assignment, I applied my new SQL skills to analyze historical credit card transactions and consumption patterns in order to identify possible fraudulent transactions.
I was asked to accomplish three main tasks:



### 1 - Data Modeling:

I created an entity relationship diagram (ERD) by inspecting the provided CSV files.I used Quick Database Diagrams to create my model.

![ERD](https://github.com/arzuisiktopbas/06-Looking_for_Suspicious_Transactions/blob/main/Images/QuickDBD-HW6.png)



### 2-Data Engineering: 
By using my database model as a blueprint,I create a database schema(above) for each of my tables and relationships. I specified data types, primary keys, foreign keys, and other constraints.
I imported the data from the corresponding CSV files.

### 3-Data Analysis: 

My data was prepared within the database, it's finally time to identify fraudulent transactions using SQL and Pandas DataFrames. 

![ID2](https://github.com/arzuisiktopbas/06-Looking_for_Suspicious_Transactions/blob/main/Images/ID2.png)

![ID18](https://github.com/arzuisiktopbas/06-Looking_for_Suspicious_Transactions/blob/main/Images/ID18.png)

![ID18&2](https://github.com/arzuisiktopbas/06-Looking_for_Suspicious_Transactions/blob/main/Images/ID2%2618.png)


It seems that consumption pattern for card holder ID #2 is regular spending, since amounts are within a certain range. However, It is obvious that card holder ID #18 has different spending habits. There are some huge purchases periodicly. These purchases need to be investigated as they are likely to be fraudulent.



![ID25](https://github.com/arzuisiktopbas/python-homework/blob/main/Homework%236/Images/ID25.png)

Although the transactions of card holder ID # 25 seems spend small amounts, large spending is made almost every month. The card holder must be warned in order to aware about these transactions.

---
