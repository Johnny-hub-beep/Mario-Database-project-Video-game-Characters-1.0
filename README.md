# 🎮 Mario Video Game Character Database

This project is a PostgreSQL-based database that stores and manages video game character data and their associated sounds.

## 📌 Overview
The database models relationships between characters and their sound effects using structured tables and SQL queries. It demonstrates how relational databases handle one-to-many relationships.

## 🧱 Database Structure

### Characters Table
- character_id (Primary Key)
- name
- homeland
- favorite_color

### Sounds Table
- sound_id (Primary Key)
- filename
- character_id (Foreign Key)

## 🔗 Key Features

- FULL JOIN to combine characters and their sounds
- One-to-many relationship (one character → multiple sounds)
- Data manipulation using:
- SELECT
- DELETE
- INSERT
- Safe deletion practices using conditions

## 💻 Example Query

sql SELECT * FROM characters FULL JOIN sounds ON characters.character_id = sounds.character_id;

## 🚀 What I Learned

- How relational databases organize and connect data
- The difference between primary keys and foreign keys
- How JOIN operations work (INNER, LEFT, FULL)
- How to safely update and delete data using SQL

## 🛠️ Technologies Used

- PostgreSQL
- SQL

## 👤 Author

Johnny
