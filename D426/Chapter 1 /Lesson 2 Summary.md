# 2.1 Relational model

## Database Model

- conceptual framework for database systems with three parts

1. Data Structures - Prescribe how data is organized
2. Operations - Manipulate data structures
3. Rules - govern valid data

- A set is an unordered collectiof of elements
enclosed in braces. EX: {a, b, c}
- A tuple is an order collection of elements enclosed in parentheses EX: (a, b, c)

## Relational Rules

- are part of the relational model and govern data in every relational database

1. Unique primary key - all tables have a primary key column, or group of columns, in which values may not repeat
2. Unique column names - Different column of the same table have different names
3. No duplicate rows - No two rows of the same table have identical values

## Business Rules

- Based on business policy and specific to a particular database
- EX: All rows of the Employee table must have a valid entry in the DepartCode column

- Relational rules are implemented as SQL constraints and enforced by the database system.
- Business rules are discovered during database design and, like relational rules, often implemented as SQL constraints.

## 2.2 Structured Query Language

### SQL sublanguages

The SQL language is divided into five sublanguages:

- Data Definition Language (DDL) defines the structure of the database.
- Data Query Language (DQL) retrieves data from the database.
- Data Manipulation Language (DML) manipulates data stored in a database.
- Data Control Language (DCL) controls database user access.
- Data Transaction Language (DTL) manages database transactions.

## 2.3 Managing databases
