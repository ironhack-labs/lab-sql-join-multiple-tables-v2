![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# Lab | SQL Joins on multiple tables (v2)

In this lab, you will be using the [Sakila](https://dev.mysql.com/doc/sakila/en/) database of movie rentals.

### Instructions

1.  Write a query to display for each store its store ID, city and country.
2.  Write a query to display how much benefit amount, in dollars, each store brought in.
3.  What is the average running time of films by category?
4.  Which film categories are longest on average?
5.  Display the most frequently rented movies in descending order.

***Hint 1***: This lab is especially challenging as the queries involve joins with multiple tables. Keep calm, take a cup of coffee and go step by step with each query. Nobody can build such complex queries in a twinkle of an eye. Remember the steps mentioned in class:

- Determine which tables contain the columns you want
- Determine if there is a common column for both tables (you will need in in `on` section of the join). Otherwise, you will need another table with a common column with both. 
- Determine which table you want to use as `left table` (will go right after the `from`) and which table will be the `right table` (will go right after the `join`)
- Determine from which table you want all the records (this will tell you which type of `join` you need)
- Create the query

***Hint 2***: Construct the joins one by one, checking the output afterward. If you are satisfied with the result add the next one, otherwise fix it. Then, join the resulting table with the next one and check again the output and so on. This process takes time, so be patient and go step by step building your query incrementally.