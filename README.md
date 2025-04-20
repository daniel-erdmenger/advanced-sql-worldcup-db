# Advanced SQL World Cup Database 🏆

A relational database project built with PostgreSQL, designed to explore and analyze historical FIFA World Cup tournament data using advanced SQL queries and normalized schema design.

This project is part of the [freeCodeCamp Relational Database Certification](https://www.freecodecamp.org/), showcasing real-world database modeling, data manipulation, and complex analytical querying.

---

##  Features

-  Fully normalized relational schema (teams, games, years, rounds)
-  Complex SQL queries using JOINs, subqueries, GROUP BY, HAVING, and aggregate functions
-  Referential integrity with foreign key constraints
-  Automated data insertion using Bash scripting
-  Data analysis on goals, winners, matchups, and tournament history

---

##  Project Structure

```bash
.
├── worldcup.sql             # SQL script to create tables and schema
├── insert_data.sh           # Bash script to populate the database
├── queries.sql              # Set of advanced SQL queries for analysis
├── README.md                # This file
