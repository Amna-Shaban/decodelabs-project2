# Data Integration CRUD System

A robust backend application developed as part of the **Decodelabs Backend Development Internship (Project 2)**. This project focuses on integrating data from various formats and exposing a clean RESTful API to perform standard CRUD (Create, Read, Update, Delete) operations using Node.js and Prisma.

---

## 🚀 Project Overview

The **Data Integration CRUD System** acts as a middleware pipeline that ingests data from multiple external sources, transforms and validates it, and stores it securely within a database. It exposes a set of standard API endpoints, enabling seamless data manipulation and consumption.

### Key Features
* **Data Ingestion & Parsing:** Integration and parsing of incoming data structures (e.g., JSON, CSV).
* **Robust CRUD Architecture:** Standardized REST API endpoints handling full data lifecycles.
* **Type-Safe Database Management:** Leveraging Prisma ORM for efficient schema modeling and database queries.
* **Error Handling & Validation:** Built-in middleware providing clear HTTP response codes and descriptive error messages.

---

## 🛠️ Tech Stack

* **Backend Environment:** Node.js
* **Framework:** Express.js
* **ORM:** Prisma
* **Database:** SQLite (or PostgreSQL/MySQL as defined in `schema.prisma`)
* **API Testing:** Postman / cURL

---
## 📂 Project Structure

```text
dataintegration-crud/
│
├── prisma/
│   └── schema.prisma        # Prisma database models and configuration
│
├── src/
│   └── server.js            # Main entry point and Express application setup
│
├── .gitignore               # Excluded files (node_modules, .env)
├── package.json             # Project metadata and dependencies
└── README.md                # Project documentation
```
---


## 🧑‍💻 Developer

**Amna Shaban**  
*Backend Engineering Intern at Decodelabs*  
