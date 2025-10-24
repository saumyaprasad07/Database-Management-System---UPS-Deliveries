# 🚚 UPS Logistics Database Management System

A **MySQL-based database project** designed to streamline and optimize logistics operations for UPS Deliveries. The system models real-world logistics workflows—managing customers, shipments, warehouses, vehicles, and employees—to ensure efficient data management, operational tracking, and performance analytics.

---

## 📊 Project Overview

This project replicates the logistics operations of a delivery company by developing a **relational database management system (RDBMS)** that:
- Tracks shipments, deliveries, and warehouse operations  
- Optimizes resource allocation and delivery scheduling  
- Supports analytical queries for business reporting and decision-making  

The database was developed and implemented in **MySQL Workbench**, emphasizing normalization, indexing, and referential integrity.

---

## 🧠 Objectives

- Design and implement a relational database reflecting UPS logistics workflows.  
- Establish logical relationships between entities such as **Customers**, **Shipments**, **Employees**, and **Warehouses**.  
- Minimize redundancy and anomalies using **Third Normal Form (3NF)** normalization.  
- Apply **indexing and query optimization** to improve performance.  
- Provide a foundation for analytics and business intelligence reporting.

---

## 🏗️ Database Design

### Entity–Relationship Diagram (EER)
The system models the relationships among entities that drive UPS delivery operations.

**Key Entities:**
- **Customer:** Stores customer contact and address details.  
- **Shipment:** Tracks packages, costs, delivery dates, and shipment status.  
- **Warehouse:** Stores and manages inventory and distribution centers.  
- **Employee:** Represents delivery staff and logistics managers.  
- **Vehicle:** Manages delivery fleet information and assignments.  
- **Location:** Contains city and province details for routing.

*(You can insert your actual EER diagram here — e.g., `![EER Diagram](assets/eer_diagram.png)`).*

---

## ⚙️ Tools & Technologies

| Category | Tools/Technologies |
|-----------|--------------------|
| Database | MySQL, MySQL Workbench |
| Modeling | EERD (Enhanced Entity–Relationship Diagram) |
| Optimization | Indexing, CTEs, Window Functions |
| Documentation | Draw.io, Excel, PDF Reports |
| Project Management | BRD, TRD, Project Charter |

---

## 🧩 Key Features

- 📦 **Shipment Tracking:** Manage delivery status, dates, and routes.  
- 🧭 **Warehouse Management:** Track inventory levels and optimize storage.  
- 👷 **Employee Allocation:** Manage staff roles and delivery responsibilities.  
- 🚗 **Fleet Management:** Maintain records of delivery vehicles and assignments.  
- 📈 **Analytical Capability:** Schema supports performance and cost analysis.  

---

## 🧮 Normalization

The database schema is normalized up to **Third Normal Form (3NF)** to:
- Remove redundancy,  
- Ensure referential integrity, and  
- Simplify future scalability and updates.  

---

## ⚡ Setup and Execution

Follow these steps to set up and run the project on your local system:

### **Prerequisites**
- Install [MySQL Server](https://dev.mysql.com/downloads/mysql/)  
- Install [MySQL Workbench](https://dev.mysql.com/downloads/workbench/)  

### **Steps**
1. **Clone the repository:**
   ```bash
   git clone https://github.com/saumyaprasad07/Database-Management-System-UPS-Deliveries.git
   cd Database-Management-System-UPS-Deliveries

