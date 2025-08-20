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
1. Total Seats
2. What are the total number of seats available for election in each state?
3. Total seats won BY NDA Alliance
4. Seats Won by NDA Alliance Parties
5. Total Seats Won by I.N.D.I.A. Allianz
6. Seats Won by I.N.D.I.A Alliance Parties
7. Adding a new column field in the table partywise_results to get the party allianz as NDA or I.N.D.I.A
8. Add party alliance as NDA Allianz
9. Add party alliance as I.N.D.I.A Allianz
10. Add other party alliance as Other.

### Complex
11. Winning candidate's name, their party name, total votes, and the margin of victory for a specific state and constituency?
12. Winning candidate's name, their party name, total votes, and the margin of victory for a specific state and constituency?
13. What is the distribution of EVM votes versus postal votes for candidates in a specific constituency?
14. Which party won the most seats in s State, and how many seats did each party win?
15. What is the total number of seats won by each party alliance (NDA, I.N.D.I.A, and OTHER) in each state for the India Elections 2024
16. Which candidate received the highest number of EVM votes in each constituency (Top 10)?
17. Which candidate won and which candidate was the runner-up in each constituency of State for the 2024 elections?
18. For the state of Maharashtra, what are the total number of seats, total number of candidates, total number of parties, total votes (including EVM and postal), and the breakdown of EVM and postal votes?

## Project Focus

This project primarily focuses on developing and showcasing the following SQL skills:
