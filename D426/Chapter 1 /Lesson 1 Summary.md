# Chapter 1 Terms

## DataBase Basics

### Database Administrator

- Responsible for securing the database system against unauthorized users

### Database Designer

- Determines the format of each data element and overall database structure.

### Database Programmer

- Develops computer programs that utilize a database

## Database User

- Consumer of data in a database

## Database Systems

### Architecture

#### Query Procesor  

- Interprets Queries, creates a plan to modify database or retrieve data and returs query results to the application.

#### Storage Manager

- Translate the query processor instructions into low-lever file system commands that modify or retrieve data

##### Transaction Manager

- Ensures transactions are properly executed. Prevent conflicts between concurrent transactions and also restore the database to a consistent state in event of system failure.

#### Log

- file containing a complete record of all inserts updates and deletes processed by database.

#### Catalog

- Also known as data dictionary

## Database Design and programming

## Analysis

[analysis has many alrenative names such as conceptual design, entity-relationship modeling and requirements definition]

- The analysis phase specifies database requirements without a regard to a specific database system
- Requirements are represented as entities, relationships and attributes.

- An *entity* is a person, place, activity or thing.
- A *relationship* is a link between entities
- An *attribute* is a descriptive property of an entity

- In ER Diagrams rectangles represent entities, lines
represent relationships and the text inside the rectangle below the entity names represent their attributes

## Logical design

[implements database requirements in a specific database system, in RDBMS logical design converts entities, relationships and attributes into tables, keys and columns]

- The logical design as specified in SQL is called a database schema

## Physical design

- Adds indexes and specifies how tables are organized on storage media
- Physical design is specified with SQL statements

## MySQL

- Sponsored by Oracle
- Runs on all major operating systems (Linux, Mac OS and Windows)
- Available in two editions
  - MySQL Community (Free edition)
  - MySQL Enterprise (paid version for commercial use)

### MySQL Command Line Client

- text interface included in the MySQL Server download

- MySql Server returns error code and description when an SQL Statement is syntatically incorrect or the  database cannot execute the statement

#### MySQL Workbench

- Is installed with MySQL Server and allows developers to execute SQL commands using an editor

- The database system that includes the World database during its installation is MySQL.
