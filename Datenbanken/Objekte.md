# Objects in Databases

## Databases & Clusters
- **Cluster** = A collection of databases

## Database Schemas
- **Schema** = Structure or class within a database that organizes tables

## Database Tables
- **Table** = Like an Excel sheet: rows and columns  
  - Each **row** = Record  
  - Each **column** = Attribute

## Records
- Contain the actual data within a table

# Logical Structures

## Views
- **View** = A virtual table based on a SELECT statement  
- Example: Display all employees over 60 years old

`CREATE VIEW over_60 AS SELECT * FROM employees WHERE age > 60;`
# Indexing and Index Types

## Why an Index is Faster
Indexes allow the database to find data more quickly, similar to a book's index that points directly to pages instead of scanning the whole book.

## How to Search Data, e.g., using:
* **GiST (Generalized Search Tree)** – useful for complex data types like geometric shapes  
* **B-Tree** – ideal for balanced hierarchical searching, often for numeric or textual data  
* **GIN (Generalized Inverted Index)** – optimized for searching elements in arrays or full-text search

# Functions and Procedures

## Scripts to Execute Commands
Functions and procedures are reusable scripts stored in the database that can perform tasks or calculations on data.

# Triggers

## Scripts that Execute Automatically
Triggers are scripts that automatically run when certain events occur in the database, like inserting or updating records.

#

![Objects](https://github.com/julius13235/Lerntagebuch/blob/main/Pictures/Objekte.png?raw=true)