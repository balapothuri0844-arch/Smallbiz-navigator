
# SmallBiz Navigator – Relational Database System

## 📌 Project Overview

SmallBiz Navigator is a **relational database system designed for small businesses** to efficiently manage employees, payroll, attendance, projects, and organizational assets.

The system centralizes business operations into a structured **MySQL database architecture**, enabling businesses to maintain employee records, track attendance, manage payroll, and monitor project activities.

This project demonstrates how **data modeling and relational database design** can be applied to solve real-world business management problems.


## 🎯 Objective

* Design a scalable **relational database system** for small business operations
* Model real-world entities such as employees, departments, payroll, and projects
* Implement relationships between entities using **primary keys and foreign keys**
* Improve business efficiency through structured data storage and management

## 📊 System Description

The SmallBiz Navigator system focuses on **employee and business management operations**.

### Core Modules

* Employee Management
* Attendance Tracking
* Payroll Management
* Leave Management
* Department Management
* Employee Training Records
* Asset Management
* Project and Task Management
* Bank Information Tracking

These modules interact through relational database tables to maintain **data consistency and integrity**.

## 🧠 Database Architecture

The system follows a **Relational Database Model**.

The **Employee table acts as the central entity**, connected to multiple supporting tables such as:

* Department
* Address
* Attendance
* Salary
* Leave Records
* Training
* Experience
* Bank Information
* Assets
* Projects

This design ensures **efficient data retrieval and structured relationships between business entities**.

## 📊 Entity Relationship Diagram

### Employee Management Module

![Employee ER Diagram](smallbiz-employee-module-erd.png)

This diagram illustrates relationships between the employee entity and related modules such as attendance, payroll, department, and training.

### Complete Database Schema

![Full Database ER Diagram](smallbiz-full-database-erd.png)

The full ER diagram represents the overall structure of the SmallBiz Navigator system, including asset management, logistics, and project workflows.

## ⚙️ Project Workflow

1. **Requirement Analysis**

   * Identify business processes involved in small enterprise management

2. **Data Modeling**

   * Define entities and relationships using ER diagrams

3. **Database Design**

   * Create relational schema with tables, keys, and constraints

4. **Implementation**

   * Implement database schema using MySQL

5. **Testing and Validation**

   * Validate relationships and test queries for business operations

## 🛠 Technologies & Tools Used

* **Database:** MySQL
* **Database Design Tool:** MySQL Workbench
* **Diagram Tools:** Draw.io / ER Modeling Tools
* **Documentation:** Microsoft Word
* **Version Control:** Git & GitHub

## 🚀 How to Run the Project

1. Clone this repository:

```bash
git clone https://github.com/balapothuri0844-arch/Smallbiz-navigator.git
```

2. Import the database schema into **MySQL Workbench**

3. Create the required tables based on the ER diagram

4. Populate the database with sample employee and business data

5. Execute SQL queries to manage business operations such as payroll tracking, attendance monitoring, and employee record management.

## 📂 Project Files

* **proposal_proj.pdf** – Initial project proposal
* **group25_designphase.docx** – Database design documentation
* **5707 Assignment 4.2.pdf** – SQL queries and implementation details
* **ER Diagrams** – Database schema representation

## 🔮 Future Improvements

* Web-based business dashboard
* Integration with payroll systems
* Automated reporting and analytics
* Role-based user access control
* Cloud database deployment

## 👨‍💻 Authors

Bala Phaneendra Pothuri
University Of North Texas

University of North Texas
INFO 5707 – Data Modeling
