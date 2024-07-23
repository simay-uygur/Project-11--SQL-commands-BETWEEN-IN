# Project-11--SQL-commands-BETWEEN-IN
These are some queries that is for the assignment in Patika website.

The given tasks are:

List all columns in the film table where the replacement cost is greater than or equal to 12.99 and less than 16.99. (Use the BETWEEN - AND structure.)
List the first_name and last_name columns in the actor table where the first_name is 'Penelope', 'Nick', or 'Ed'. (Use the IN operator.)
List all columns in the film table where the rental_rate is 0.99, 2.99, or 4.99 AND the replacement_cost is 12.99, 15.99, or 28.99. (Use the IN operator.)

The Queries are: 

-- Active: 1721726315493@@localhost@5432@dvdrental@public

-- Task1

SELECT *
FROM film
WHERE replacement_cost BETWEEN 12.99 AND 16.98;


-- Task 2
SELECT first_name, last_name
FROM actor
WHERE first_name IN('Penelope', 'Nick', 'Ed');



SELECT *
FROM film
WHERE rental_rate IN (0.99, 2.99, 4.99) AND replacement_cost IN(12.99, 15.99, 28.99 ); 


