# 🏅 Olympics DataHub

A comprehensive **PostgreSQL-based relational database management system** designed to model and manage Olympic Games data. The project demonstrates database design principles through **ER modeling**, **BCNF normalization**, **relational schema design**, and advanced **SQL queries** for analytical reporting.

---

## 📌 Features

- Designed a normalized relational database with **23 interconnected tables**.
- Modeled Olympic editions, athletes, sports, disciplines, events, venues, countries, teams, sponsors, and broadcasting.
- Applied **BCNF normalization** to reduce redundancy and maintain data integrity.
- Implemented **Primary Keys**, **Foreign Keys**, and **Many-to-Many relationships**.
- Populated the database with realistic sample data.
- Developed advanced analytical SQL queries using:
  - JOINs
  - Aggregate Functions
  - Common Table Expressions (CTEs)
  - Window Functions
  - Ranking Functions
  - Subqueries

---

## 🛠 Tech Stack

- PostgreSQL
- SQL
- ER Modeling
- Relational Database Design

---

## 📂 Repository Structure

```
Olympics-DataHub
│
├── schema
│   ├── create_tables.sql
│   └── insert_data.sql
│
├── queries
│   └── analytical_queries.sql
│
├── diagrams
│   ├── Olympics_ERD.dia
│   ├── ER_Diagram.png
│   └── Relational_Schema.png
│
├── docs
│   └── Database_Design.pdf
│
└── README.md
```

---

## 🗂 Database Schema

The project consists of **23 normalized tables**, including:

- Olympic Edition
- Sport
- Discipline
- Event
- Venue
- Country
- Athlete
- Team
- Participation
- Sponsor
- Contract
- Coach
- Broadcast
- Media Agency
- Medical Test
- Doping Test

and multiple junction tables for many-to-many relationships.

---

## 🖼 Entity Relationship Diagram

![ER Diagram](diagrams/ER_Diagram.png)

---

## 📑 Relational Schema

![Relational Schema](diagrams/Relational_Schema.png)

---

## 📊 Sample Analytical Queries

The project includes SQL queries for various stakeholder perspectives, such as:

### IOC Administrators
- Medal tally by country
- Running cumulative medal count
- Event scheduling
- Host nation performance
- Gender participation analysis

### National Olympic Committees
- Athlete participation across editions
- Discipline-wise athlete ranking
- Country-wise athlete lists
- Multi-edition medalists

### Media Agencies
- Most broadcasted events
- Agency-wise sports coverage
- Broadcast statistics

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/<your-username>/Olympics-DataHub.git
```

### 2. Create a PostgreSQL database

```sql
CREATE DATABASE olympics;
```

### 3. Execute the schema

Run

```
schema/create_tables.sql
```

### 4. Populate the database

Run

```
schema/insert_data.sql
```

### 5. Execute analytical queries

Run

```
queries/analytical_queries.sql
```

---

## 🎯 Learning Outcomes

Through this project, we explored:

- Relational Database Design
- ER Modeling
- BCNF Normalization
- Functional Dependencies
- SQL Query Optimization
- Window Functions
- Database Constraints
- Complex Joins and Aggregations

---

## 👥 Team Members

- **Shubh Patel** (Group Representative)
- Yajat Solanki
- Yashrajsinh Solanki
- Yash Oza

---

## 📜 License

This project was developed as part of the **IT214 – Database Management System** course at **Dhirubhai Ambani University** for academic purposes.
