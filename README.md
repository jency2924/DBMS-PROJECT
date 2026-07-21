# ShopEasy – E-Commerce Order Management Database System

## Week 1 – Requirement Analysis ,BRD,SRS

###  Project Overview
ShopEasy is an E-Commerce Order Management Database System developed to manage the core operations of an online shopping platform. The project focuses on creating a centralized database that efficiently manages customers, products, inventory, suppliers, orders, payments, shipments, and customer reviews.

The primary objective of Week 1 is to analyze the business requirements, identify business problems, and prepare the necessary requirement specification documents before database design and implementation.

---

##  Objectives

- Analyze business requirements.
- Identify existing business problems.
- Propose an effective database solution.
- Define project scope.
- Identify stakeholders.
- Prepare Requirement Analysis Document.
- Prepare Business Requirement Document (BRD).
- Prepare Software Requirement Specification (SRS).

---

##  Documents Included

- Business Requirement Document (BRD)
- Requirement Analysis Document
- Software Requirement Specification (SRS)

---

##  Business Problem

The organization currently faces several operational challenges:

- Manual customer record management
- Duplicate and inconsistent data
- Inventory tracking issues
- Slow order processing
- Inefficient payment management
- Shipment tracking difficulties
- Limited business reporting
- Human errors due to manual operations

---

##  Proposed Solution

The ShopEasy database system provides a centralized platform to manage:

- Customer Information
- Product Categories
- Products
- Suppliers
- Inventory
- Orders
- Payments
- Shipments
- Customer Reviews
- Business Reports

---

##  Core Database Entities

- Customer
- Category
- Product
- Supplier
- Order
- Order Details
- Payment
- Shipment
- Review

---

##  Major Business Processes

1. Customer Registration
2. Product Management
3. Category Management
4. Inventory Tracking
5. Order Processing
6. Payment Management
7. Shipment Tracking
8. Customer Review Management
9. Business Report Generation

---

##  Stakeholders

- Customer
- Administrator
- Supplier
- Warehouse Staff
- Delivery Staff
- Finance Team
- Management

---

##  Functional Requirements

- Register customers
- Manage products and categories
- Maintain supplier records
- Update inventory
- Process customer orders
- Record payments
- Track shipments
- Store customer reviews
- Generate business reports

---

##  Non-Functional Requirements

- Security
- Reliability
- Scalability
- Availability
- Data Integrity
- High Performance
- Maintainability
- Backup & Recovery
- User-Friendly Interface
- Compatibility

---

##  Expected Benefits

- Centralized data management
- Reduced data redundancy
- Faster order processing
- Better inventory control
- Accurate payment tracking
- Efficient shipment monitoring
- Improved customer satisfaction
- Better business reporting
- Increased operational efficiency

---

##  Technologies (Upcoming Weeks)

- MySQL
- SQL
- ER Diagram
- Normalization
- DBMS Concepts

---

##  Week 1 Deliverables

- ✅ Business Requirement Document (BRD)
- ✅ Requirement Analysis Document
- ✅ Software Requirement Specification (SRS)

---

##  Project Status

**Week 1 Completed**

Requirement analysis and documentation have been successfully completed. The next phase will focus on database design, ER modeling, normalization, and SQL implementation.

---





# Week 2 – Entity and Relationship Analysis

## Project Title
**ShopEasy – E-Commerce Order Management Database System**

## Overview
In Week 2, the data requirements of the ShopEasy – E-Commerce Order Management Database System were analyzed based on the Software Requirement Specification (SRS) prepared in Week 1. This phase focused on identifying all the entities involved in the system, defining their attributes, determining primary keys and foreign keys, applying database constraints, and analyzing the relationships and cardinality between entities. These activities provide the foundation for an efficient and normalized relational database design.

## Objectives
- Identify all entities required for the system.
- Define attributes for every entity.
- Identify Primary Keys (PK) and Foreign Keys (FK).
- Apply database constraints such as NOT NULL, UNIQUE, DEFAULT, and CHECK.
- Analyze relationships between entities.
- Identify relationship cardinality (One-to-One, One-to-Many, and Many-to-Many).
- Prepare Entity Analysis and Entity Relationship Analysis reports.

## Files Included
```
Week2/
│── Entity_Analysis_Report.docx
│── Entity_Relationship_Analysis.docx
│── README.md
```

## Entity Analysis Summary
The Entity Analysis Report identifies the core entities of the ShopEasy system, including Customer, Category, Product, Supplier, Order, Order Details, Payment, Shipment, and Review. Each entity is defined with its attributes, Primary Key (PK), Foreign Key (FK), and database constraints such as NOT NULL, UNIQUE, DEFAULT, and CHECK. This analysis ensures data integrity, minimizes redundancy, and supports efficient database management.

## Entity Relationship Analysis Summary
The Entity Relationship Analysis Report explains how the entities are connected within the database. It defines the relationships between entities, identifies the appropriate cardinality (One-to-One and One-to-Many), and describes how these relationships support customer management, product management, order processing, payment tracking, shipment tracking, and review management. The relationship model ensures referential integrity and provides a clear structure for database implementation.

## Learning Outcomes
- Understood the process of entity identification.
- Defined entity attributes, primary keys, and foreign keys.
- Applied database constraints to maintain data accuracy and consistency.
- Analyzed relationships and cardinality between entities.
- Developed a strong foundation for ER Diagram creation, normalization, and SQL table design.



##  Project Status
** Week 2 successfully completed ** 

the Entity Analysis and Entity Relationship Analysis for the ShopEasy – E-Commerce Order Management Database System. The reports clearly define the database entities, attributes, keys, constraints, relationships, and cardinality required for the system. These deliverables serve as the foundation for the next phase of the project, including ER Diagram development, database normalization, and SQL implementation.





# WEEK-3 README

## Project Title

**ShopEasy – E-Commerce Order Management Database System**

**Week-3: Entity Relationship (ER) Diagram and Relational Schema Design**

---

## Objective

The objective of Week-3 is to design the **Entity Relationship (ER) Diagram** and **Relational Schema** for the ShopEasy E-Commerce Order Management Database System. This phase identifies the entities, attributes, relationships, primary keys, foreign keys, and cardinality to create a well-structured relational database.

---

## Tasks Completed

* Identified all entities required for the system.
* Defined attributes for each entity.
* Assigned Primary Keys (PK) and Foreign Keys (FK).
* Designed the Entity Relationship (ER) Diagram.
* Defined relationships between entities.
* Specified cardinality (1:1 and 1:M).
* Created the Relational Schema for database implementation.

---

## Entities

* Customer
* Category
* Supplier
* Product
* Order
* Order_Details
* Payment
* Shipment
* Review

---

## Relationships

* Customer **Places** Order
* Order **Has** Order_Details
* Order_Details **Contains** Product
* Product **Belongs To** Category
* Supplier **Supplies** Product
* Order **Has** Payment
* Order **Has** Shipment
* Customer **Writes** Review
* Product **Receives** Review

---

## Cardinality

* Customer → Order (1:M)
* Category → Product (1:M)
* Supplier → Product (1:M)
* Order → Order_Details (1:M)
* Product → Order_Details (1:M)
* Order → Payment (1:1)
* Order → Shipment (1:1)
* Customer → Review (1:M)
* Product → Review (1:M)

---

## Deliverables

* ER Diagram
* ER Diagram Design Report
* Relational Schema
* README Document

---

## Expected Outcome

The Week-3 deliverables provide a complete logical database design for the ShopEasy system. The ER Diagram and Relational Schema ensure proper relationships, maintain data integrity, reduce redundancy, and serve as the foundation for database implementation in the upcoming phases.

---

## Conclusion

  the database design phase by creating the ER Diagram and Relational Schema. The designed database structure efficiently represents the relationships among customers, products, suppliers, orders, payments, shipments, and reviews, ensuring a scalable and reliable E-Commerce Order Management System.ed 


##WEEK-3 SUCESFULLY COMPLETED
