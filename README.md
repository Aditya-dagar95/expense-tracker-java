# Expense Tracker

A backend-focused expense tracking application built with **Java, Spring Boot, JPA/Hibernate, and MySQL**.

## 🚀 Project Status

Currently under development.

### Completed

* MySQL database design
* User entity
* Spring Boot project setup
* JPA/Hibernate configuration

### In Progress

* Expense REST APIs
* CRUD operations
* API testing with Postman

### Planned

* Category management
* User authentication
* Expense filtering and searching
* Monthly expense summaries
* Frontend
* Dashboard and analytics

## 🛠️ Tech Stack

* Java
* Spring Boot
* Spring Data JPA
* Hibernate
* MySQL
* Maven
* Postman
* Git & GitHub

## 📁 Project Structure

```text
expense-tracker/
├── src/
│   ├── main/
│   │   ├── java/
│   │   └── resources/
│   └── test/
├── database/
│   └── schema.sql
├── .gitignore
├── pom.xml
└── README.md
```

## 🗄️ Database

The application uses MySQL for persistent data storage.

Main entities:

* Users
* Expenses
* Categories

## 🔌 Planned REST APIs

| Method | Endpoint         | Purpose           |
| ------ | ---------------- | ----------------- |
| POST   | `/expenses`      | Create an expense |
| GET    | `/expenses`      | Get expenses      |
| DELETE | `/expenses/{id}` | Delete an expense |

More endpoints will be added as development continues.

## ▶️ How to Run

1. Clone the repository.
2. Create the MySQL database.
3. Configure the database connection.
4. Run the Spring Boot application using IntelliJ or Maven.
5. Test the APIs using Postman.

## 📌 Future Improvements

* Authentication and authorization
* Expense categories
* Filtering by date/category
* Monthly spending reports
* Dashboard
* Frontend integration
* Deployment
