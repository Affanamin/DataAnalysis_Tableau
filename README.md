# Data Analysis through Tableau Dashboard

## Setup mysql through given link

Just follow simple steps shown in given video to install mysql on your system 
https://www.youtube.com/watch?v=WuBcTJnIuzo

SQL database dump is in db_dump.sql file above. Download db_dump.sql file to your system and import it as per instructions given in the tutorial video.


## Simple Data Analysis Through SQL Queries

1. Show all customer records

  `SELECT * FROM customers;`

2. Show total number of customers

  `SELECT count(*) FROM customers;`

3. Show transactions for Chennai market (market code for chennai is Mark001)

  `SELECT * FROM transactions where market_code='Mark001'`

4. Show distrinct product codes that were sold in chennai

  `SELECT distinct product_code FROM transactions where market_code='Mark001';`

5. Show transactions where currency is US dollars

  `SELECT * from transactions where currency="USD"`
