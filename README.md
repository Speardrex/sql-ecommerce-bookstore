#  ![Logo](https://github.com/Speardrex/sql-ecommerce-bookstore/blob/main/caleb-woods-fulXJYIvRi8-unsplash.jpg) sql-ecommerce-bookstore
## Project Overview
The Online Book Store project is a database-driven application designed to manage books, customers, and orders efficiently. The system provides structured storage of data related to books, their genres, authors, availability, customers’ details, and orders placed. SQL queries are applied to retrieve insights such as sales reports, customer activity, stock levels, and revenue generation. The project demonstrates practical applications of SQL in managing and analyzing real-world datasets for e-commerce-like platforms.
## Entity Relationship Diagram (ERD)
![ERD](https://github.com/Speardrex/sql-ecommerce-bookstore/blob/main/Database%20ER%20diagram%20(crow's%20foot).png)


## Database Schema

The project uses five main tables:

1. **Constituencywise Results**: Contains information about constituencywise results.
   - `Parliament Constituency`: name and the number together of each constituency.
   - `Constituency Name`: Name of the Constituency.
   - `Winning Candidate`: Person who got elected.
   - `Total Votes`: Number of votes gained.
   - `Margin`: Won by the number of votes.
   - `Constituency ID`: Unique identifier for each constituency.
   - `Party ID`: Unique identifier for each party.

2. **Constituencywise Details**: Detail information on candidate, votes, percentage of votes.
   - `Candidate`: A candidate is ultimately an applicant for a position.
   - `Party`: Name of the party.
   - `EVM Votes`:Electronic Voting Machine votes.
   - `Postal Votes`: Votes by physically attending.
   - `Total Votes`: Sum of EVM & Postal votes.
   - `% of Votes`: Percentage of votes
   - `Constituency ID`: Unique identifier for each constituency.

3. **Statewise Results**: Details about state results.
   - `Constituency`: Name of the Constituency.
   - `Const. No.`: Number for each constituency.
   - `Parliament Constituency`: name and the number together of each constituency.
   - `Leading Candidate`: A leading candidate is the person who is ahead in votes.
   - `Trailing Candidate`: A trailing candidate is a person who is behind in votes.
   - `Margin`: Indicates how much one candidate is ahead or behind another.
   - `Status`: Whether votes are still being counted, certified, or contested.
   - `State ID`: Unique identifier for each state.
   - `State`: Name of the state.

4. **Partywise Results**: Stores result depending on parties.
   - `Party`: Name of the party.
   - `Won`: Number of seats won.
   - `Party ID`: Unique identifier for each party.

5. **States**: Contains information about state.
   - `State ID`: Unique identifier for each state.
   - `State`: Name of the state.

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
