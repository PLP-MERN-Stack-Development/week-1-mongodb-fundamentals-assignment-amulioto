# 📚 MongoDB Fundamentals Assignment – PLP Bookstore Project

This is my completed assignment for learning MongoDB basics. It includes creating a database, inserting book data, performing CRUD operations, running advanced queries, using aggregation pipelines, and adding indexes for optimization.

---

## 🧠 What This Project Includes

I created a MongoDB project with the following:

- A database called `plp_bookstore`
- A `books` collection with 12 sample book documents
- Queries to:
  - Create, update, and delete documents
  - Filter, sort, and paginate data
  - Analyze data using aggregation
  - Add indexes and check performance with `.explain()`

---

## 📂 Files in This Project

| File              | Description |
|-------------------|-------------|
| `insert_books.js` | JavaScript file to insert book data into the `books` collection |
| `queries.js`      | Contains all the MongoDB queries I wrote for the assignment |
| `screenshot.PNG`  | Screenshot of my database setup in MongoDB Compass |
| `README.md`       | This file, explaining my project and how to run it |
| `Week1-Assignment.md` | Assignment instructions from the instructor |

---

## 🛠️ How to Run the Project

### ✅ Prerequisites

Make sure you have one of the following:

- MongoDB installed locally OR  
- A free [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) cluster

You also need:

- [MongoDB Shell (mongosh)](https://www.mongodb.com/try/download/shell)  
  or  
- [MongoDB Compass GUI](https://www.mongodb.com/products/compass)

---

### 🧪 Steps to Run

1. **Open your terminal or mongosh**
2. **Insert the book data**:

   ```bash
   mongosh < insert_books.js
Run my queries:

Open the queries.js file and copy each query into your shell to test it step-by-step.

You can also explore the database using MongoDB Compass.

✅ Tasks Completed
📌 Task 1: MongoDB Setup
Created the plp_bookstore database

Created the books collection

📌 Task 2: CRUD Operations
Inserted multiple book documents

Updated book price and added new fields

Deleted a book using deleteOne()

📌 Task 3: Advanced Queries
Found books by genre, author, and year

Used projection and sorting

Implemented pagination with limit() and skip()

📌 Task 4: Aggregation Pipelines
Calculated average book price by genre

Found the most frequent author

Grouped books by publication decade

📌 Task 5: Indexing
Created single and compound indexes

Checked performance improvements using .explain("executionStats")

📸 Screenshot
A screenshot of my MongoDB Compass setup is saved in:

screenshot.PNG
📚 Helpful Resources I Used
MongoDB Documentation

MongoDB University (Free Courses)

Compass GUI Tool

MongoDB Shell Guide

🙋‍♂️ About Me
I'm a student learning the MERN stack through the Power Learn Project. This is one of my MongoDB projects showing what I’ve learned about databases.

Thank you for reviewing my project!