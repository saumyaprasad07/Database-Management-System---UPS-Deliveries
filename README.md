# 🚚 UPS Logistics Database Management System

### 📊 A Data-Driven SQL Project for Optimizing Logistics Operations

This project focuses on designing and implementing a **relational database management system (RDBMS)** for **UPS Deliveries**, simulating real-world logistics operations such as **shipment tracking, delivery scheduling, warehouse management, and customer information**. The goal is to ensure **data integrity, query efficiency, and business process optimization** through advanced SQL and database design concepts.

---

## 🧠 Project Overview

The **UPS Logistics Database Management System** was developed to streamline logistics operations by effectively managing shipment data, delivery routes, and employee assignments.  
We designed and implemented this system using **MySQL**, adhering to **best practices in normalization, indexing, and query optimization** to enhance database performance.

---

## 🎯 Objectives

- Design a **normalized and scalable database** for logistics management.
- Implement **data modeling** using **EER Diagrams (EERD)** and **3NF normalization**.
- Apply **SQL optimization** techniques (CTEs, window functions, indexing).
- Perform **business and technical analysis** via BRD, TRD, and process modeling.
- Enable **data-driven insights** through optimized queries and reports.

---

## 🗂️ Database Design

### 🔹 Key Entities:
- **Customer**
- **Shipment**
- **Warehouse**
- **Delivery**
- **Employee**
- **Vehicle**
- **Location**

### 🔹 Relationships:
- A customer can send or receive multiple shipments.
- Each shipment is assigned to a delivery and a specific employee.
- Warehouses manage shipments through vehicle assignments and schedules.

---

## 🧩 Data Modeling

### 🏗️ EER Diagram
The **EER Diagram (Enhanced Entity-Relationship Diagram)** defines the logical structure and relationships among tables, enabling an efficient database schema.

*(EER Diagram image placeholder — Add your diagram here)*

### 🧮 Normalization
The schema was normalized to **Third Normal Form (3NF)** to eliminate redundancy and ensure data consistency.

---

## ⚙️ SQL Features Implemented

| Feature | Description |
|----------|--------------|
| **DDL** | Created tables, primary keys, foreign keys, and constraints |
| **DML** | Inserted, updated, and deleted records |
| **CTEs** | Simplified complex queries and improved readability |
| **Window Functions** | Used for ranking deliveries and performance metrics |
| **Indexes** | Optimized query performance on frequently queried columns |
| **Views** | Created to display shipment summaries and delivery analytics |
| **Joins** | Combined multiple tables for business reports |

---

## 📈 Business Analysis Documents

| Document | Description |
|-----------|-------------|
| **BRD (Business Requirements Document)** | Defines project scope, objectives, and business needs |
| **TRD (Technical Requirements Document)** | Outlines database specifications, architecture, and performance goals |
| **Project Charter** | Provides a high-level overview of goals, stakeholders, and deliverables |
| **Process Modeling (draw.io)** | Visual representation of delivery and logistics workflows |


![Built with MySQL](https://img.shields.io/badge/Built%20With-MySQL-blue)
![Status](https://img.shields.io/badge/Project%20Status-Completed-green)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow)
