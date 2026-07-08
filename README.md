<div align="center">

# 💬 Customer Feedback Management System  
### Java Swing · MySQL · JDBC · Desktop Application

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Swing](https://img.shields.io/badge/Java%20Swing-5382A1?style=for-the-badge)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![JDBC](https://img.shields.io/badge/JDBC-025E8C?style=for-the-badge)
![NetBeans](https://img.shields.io/badge/Apache%20NetBeans-1B6AC6?style=for-the-badge&logo=apachenetbeanside&logoColor=white)

</div>

---

## 🔍 Overview

**Customer Feedback Management System (CFMS)** is a **Java Swing desktop application** built to help IT organizations collect, manage, and review customer feedback using a structured MySQL-backed system.

The project demonstrates desktop GUI development, database connectivity, authentication workflows, and feedback record management using **Java, Swing, JDBC, and MySQL**.

---

## ✨ Key Features

| Feature | Description |
|---|---|
| 🔐 Login System | Supports admin/user login workflows |
| 🏢 Organization Management | Manage IT organization/company records |
| 💬 Feedback Submission | Allows users to submit customer feedback |
| 📋 Feedback Review | View and manage submitted feedback |
| 🗑️ Deleted Reviews Table | Stores deleted feedback records separately |
| 🗄️ MySQL Storage | Persists application data using SQL tables |
| 🖥️ Desktop GUI | Built using Java Swing components |

---

## 🛠️ Tech Stack

| Category | Tools / Technologies |
|---|---|
| Programming Language | Java |
| User Interface | Java Swing |
| Database Connectivity | JDBC |
| Database | MySQL |
| IDE | Apache NetBeans |
| Build System | Ant |
| Database Setup | SQL scripts |

---

## 🗂️ Database Files

The project includes SQL files for setting up the required database tables.

| SQL File | Purpose |
|---|---|
| `admin_user.sql` | Creates/administers login user data |
| `it_organizations.sql` | Stores IT organization/company information |
| `it_organization_reviews.sql` | Stores customer feedback/review records |
| `deleted_reviews.sql` | Stores deleted review records |

---

## 🧪 Testing / Validation Focus

| Area Tested | Validation Goal |
|---|---|
| Login Workflow | Verify valid and invalid login behavior |
| Form Inputs | Check required fields and input handling |
| Feedback Submission | Confirm feedback is saved correctly |
| Database Insert | Validate new records in MySQL |
| Database Retrieval | Confirm saved records display correctly |
| Delete Workflow | Verify deleted reviews are handled separately |
| JDBC Connection | Confirm application connects to MySQL correctly |
| Regression Testing | Re-check core workflows after changes |

---

## 👩‍💻 My Role

I worked on this project with a focus on **Java desktop application development, database connectivity, and workflow validation**.

My work involved:

- developing and testing Java Swing screens
- connecting the application to MySQL using JDBC
- validating login and feedback workflows
- checking database insert, retrieve, and delete operations
- testing form behavior and user interactions
- reviewing application flow from login to feedback management

---

## ▶️ How to Run

### Prerequisites

Make sure you have:

- Java JDK 8 or higher
- Apache NetBeans IDE
- MySQL Server / XAMPP / WAMP
- Project SQL files imported into MySQL

---

### Setup Steps

1. Clone the repository.

   `git clone https://github.com/SHREENITHI-TV/CFMS-desktop-application.git`

2. Open **Apache NetBeans**.

3. Go to:

   `File → Open Project`

4. Select the project folder.

5. Start your MySQL server.

6. Import the SQL files into your database:

   - `admin_user.sql`
   - `it_organizations.sql`
   - `it_organization_reviews.sql`
   - `deleted_reviews.sql`

7. Check database connection details in the source code.

   Typical values to verify:

   - database name
   - username
   - password
   - localhost port

8. Run the project from NetBeans.

---

## 🔄 Application Flow
```text
Login
  ↓
Home / Dashboard
  ↓
Manage IT Organization Details
  ↓
Submit Customer Feedback
  ↓
View / Manage Feedback
  ↓
Delete / Store Review Records
```
---

## 📌 Project Relevance

This project demonstrates practical experience with:

- Java desktop application development
- Java Swing UI workflows
- JDBC database connectivity
- MySQL-backed data management
- Form validation and workflow testing
- Database-driven application design
- Functional and regression testing basics

---

## 🚀 Future Improvements

- Add JUnit tests for validation logic
- Add role-based access control
- Add dashboard analytics for feedback trends

---

<div align="center">

### Built to practice Java desktop development, database connectivity, and feedback workflow validation.

</div>
