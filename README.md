#  ![Logo](https://github.com/Speardrex/sql-ecommerce-bookstore/blob/main/caleb-woods-fulXJYIvRi8-unsplash.jpg) sql-ecommerce-bookstore
## Project Overview
The Online Book Store project is a database-driven application designed to manage books, customers, and orders efficiently. The system provides structured storage of data related to books, their genres, authors, availability, customers’ details, and orders placed. SQL queries are applied to retrieve insights such as sales reports, customer activity, stock levels, and revenue generation. The project demonstrates practical applications of SQL in managing and analyzing real-world datasets for e-commerce-like platforms.
## Entity Relationship Diagram (ERD)
![ERD](https://github.com/Speardrex/sql-ecommerce-bookstore/blob/main/Database%20ER%20diagram.png)


## Database Schema

The project uses three main tables:

1. **Books**: Contains information about the books available in the store.
   - `Book ID`: Unique identifier for each book.
   - `Title`: Name of the book.
   - `Author`: Name of the author.
   - `Genre`: Category of the book (e.g., Fiction, Fantasy, etc.).
   - `Published Year`: Year the book was published.
   - `Price`: Price of the book.
   - `Stock`: Number of copies available.

2. **Customers**: Contains information about customers who purchase books.
   - `Name`: Full name of the customer.
   - `Party`: Name of the party.
   - `Email`: Email address of the customer (unique).
   - `Country`: Country where the customer is located.
   - `City`: City where the customer is located.

3. **Orders**: Contains information about orders placed by customers.
   - `Order ID`: Unique identifier for each order.
   - `Customer ID`: Links to the customer who placed the order.
   - `Book ID`: Links to the book being ordered.
   - `Quantity`: Number of copies of the book ordered.
   - `Total Amount`: Total price for the order (Quantity × Book Price).
   - `Order Date`: Date when the order was placed.

**Relationships**

`One customer` → many orders (a customer can place multiple orders).

`One book` → many orders (a book can be ordered by many customers).
   
## Objectives
The project is split into two tiers of questions to test SQL skills of increasing complexity:

### Intermediate
1. Retrieve all books in the “FICTION” genre.
2. Find books published after the year ‘1950’
3. List all customers from ‘Canada’
4. Show orders placed in November 2023.
5. Retrieve the total stock of books available
6. Find the details of the most expensive book
7. Show all customers who ordered more than 1 quantity of a book
8. Retrieve all order where the total amount exceeds $20
9. List all genre available in the books table
10. Find the book with the lowest stock
11. Calculate the total revenue generated from all orders

### Advance
12. Retrieve the total number of books sold for each genre
13. Find the average price of books in the ‘Fantasy’ genre
14. List customers who have placed at least 2 orders
15. Find the most frequently ordered book.
16. Show the top 3 expensive book of ‘Fantasy’ genre.
17. Retrieve the total quantity of books sold by each author.
18. List the cities where customers who spend over $30 are located.
19. Find the customer who spends the most on orders
20. Calculate the remaining stock after fulfilling all orders.

## Project Focus

This project primarily focuses on developing and showcasing the following SQL skills:

- **Data Management**: Organizing book, customer, and order data into relational tables.
- **Basic Queries**: Retrieving, filtering, and aggregating data (e.g., books by genre, orders by date, customer locations).
- **Advanced Analysis**: Performing joins, grouping, and aggregations to uncover insights like top customers, top-selling genres, most expensive books, and total revenue.
- **Decision Support**: Enabling business-focused insights such as customer spending behavior, stock analysis, and sales tracking.
- **Hands-on SQL Practice**: Building strong command over SELECT, JOIN, GROUP BY, HAVING, ORDER BY, and aggregate functions.
