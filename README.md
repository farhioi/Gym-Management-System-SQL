# Gym-Management-System-SQL
Course project: Relational database design (ER diagrams) and implementation (SQL Server) for gym member, session, and booking management. Includes stored procedures (SPs) for automation and role-based access control (RBAC).
# SQL-Database-Design-Gym

## Project Summary

This project involved the design and implementation of a relational database schema for a hypothetical gym management system using SQL Server. The system is architected to efficiently manage member data, class schedules, and booking information.

This repository showcases my ability to transition from **business requirements (Use Cases)** to **database architecture** and **SQL automation**.

## Core Skills Demonstrated

| Skill Area | Description & Technical Implementation |
| :--- | :--- |
| **Database Design & Modeling** | [cite_start]Creation of the relational model based on **Entity-Relationship Diagrams (ERDs)**[cite: 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11]. Focus on normalization and ensuring data integrity using **Foreign Keys**. |
| **SQL Automation** | Implementation of **Stored Procedures** (SPs) to automate repetitive tasks (e.g., data quality checks, reporting logic) and improve efficiency. |
| **Security & Administration** | Designing and implementing **Role-Based Access Control (RBAC)** to manage permissions for different user roles (e.g., Member, Administrator). |
| **Business Analysis** | [cite_start]Documentation of system requirements and expected behavior through detailed **Use Cases**[cite: 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11]. |

## Repository Contents

The files included demonstrate the complete design and implementation lifecycle:

* **`ER_Diagram.pdf`**: The Entity-Relationship Diagram (ERD).
* **`Use_Cases_1-10.pdf`**: Documentation detailing user interactions and system requirements.
* **`Kuntosali_tietokantamalli.xlsx - Sheet1.csv`**: The database table structure and attribute definitions.
* **`create_tables.sql`**: SQL script for creating all tables and defining relationships.
* **`stored_procedures.sql`**: SQL script containing the automation procedures and security definitions.
* **`Project_Documentation.docx`**: The full project report, including table descriptions and business logic.

## Setup Instructions

The database is designed for **SQL Server** (or a compatible SQL engine).

1.  **Download** the repository files.
2.  **Open** your preferred SQL management tool (e.g., SSMS, Azure Data Studio).
3.  **Create** a new database (e.g., `GymDB`).
4.  **Execute** the script **`create_tables.sql`** to create the schema.
5.  **Execute** the script **`stored_procedures.sql`** to add automation and access roles.

The database should now be fully configured for testing and development.
