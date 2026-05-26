# SQL Database Design and DDL Constraints Implementation

## 📌 Project Overview
This project demonstrates the creation and management of an **Employee Database** using SQL.  
It covers **DDL commands, constraints, and relationships** between tables to ensure data integrity and structured schema design.

## 🛠️ Features
- **Database Creation**: `employee_db`
- **Tables**:
  - `Departments_Info` – Stores department details
  - `Locations` – Stores office location details
  - `Employees` – Stores employee records with constraints
- **Constraints Applied**:
  - `PRIMARY KEY`, `FOREIGN KEY`
  - `NOT NULL`, `UNIQUE`
  - `CHECK` constraints for age and gender
  - `ON DELETE CASCADE`, `ON UPDATE CASCADE`
- **DDL Commands**:
  - `ALTER TABLE`, `RENAME TABLE`, `DROP TABLE`, `TRUNCATE TABLE`
- **Data Insertion** with sample employee records

## 📊 Schema Design
The database schema ensures:
- Referential integrity between `Employees`, `Departments_Info`, and `Locations`
- Validation of employee attributes (age ≥ 18, gender restricted to Male/Female)
- Automatic handling of cascading updates/deletes

## 📈 Sample Data
Example employee records inserted:

| employee_id | employee_name | gender | age | hire_date  | designation        | salary   | department_id | location_id | email                     |
|-------------|---------------|--------|-----|------------|--------------------|----------|---------------|-------------|---------------------------|
| 101         | Arun Kumar    | Male   | 28  | 2026-05-25 | Data Analyst       | 45000.00 | 3             | 2           | arun.kumar@example.com    |
| 102         | Priya Sharma  | Female | 32  | 2026-05-25 | HR Manager         | 60000.00 | 1             | 1           | priya.sharma@example.com  |
| 103         | Ravi Patel    | Male   | 26  | 2026-05-25 | Software Engineer  | 52000.00 | 3             | 4           | ravi.patel@example.com    |
| 104         | Meena Iyer    | Female | 29  | 2026-05-25 | Marketing Executive| 40000.00 | 4             | 3           | meena.iyer@example.com    |

## 🔗 ER Diagram
The Enhanced Entity-Relationship (EER) diagram illustrates:
- One-to-many relationships between departments, locations, and employees
- Constraints ensuring structured and reliable data storage

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/employee-db-sql.git
