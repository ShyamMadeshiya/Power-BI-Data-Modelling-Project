# 📊 Power BI Data Modeling Project

## 📌 Overview

This project demonstrates the process of transforming a poorly designed Power BI data model into a clean, scalable, and high-performance Star Schema suitable for business reporting and analytics.

The project focuses on identifying fact and dimension tables, cleaning and restructuring raw data, optimizing relationships, and preparing a semantic model for efficient dashboard development.

---

## 🎯 Project Objectives

• Transform an unstructured data model into a Star Schema.

• Improve report performance through optimized relationships.

• Build reusable Fact and Dimension tables.

• Remove redundant and unnecessary data.

• Apply enterprise-level data modeling standards.

• Prepare the model for scalable reporting.

---

## 🛠️ Technologies Used

• Power BI Desktop

• Power Query (M Language)

• DAX

• Data Modeling

• Star Schema

• Relationship Management

---

## 📂 Dataset Overview

The dataset represents a real-world business scenario containing multiple operational tables.

• Customers

• Products

• Orders

• Order Line Items

• Invoices

• Invoice Lines

• Payments

• Inventory

• Shipments

• Marketing Campaigns

• Exchange Rates

• Sales Targets

• Security Tables

---

The raw dataset intentionally contains:

• Many-to-many relationships

• Duplicate tables

• Poor naming conventions

• Redundant columns

• Mixed granularities

• Non-optimized relationships

---

## 🏗️ Data Modeling Process

### Phase 1 – Data Exploration

• Analyzed business entities.

• Identified Fact and Dimension tables.

• Reviewed table granularity.

• Examined existing relationships.

---

### Phase 2 – Dimension Modeling

• Created clean Customer and Product dimensions.

• Merged related tables.

• Removed duplicate records.

• Eliminated unnecessary columns.

• Standardized naming conventions.

• Generated surrogate keys where required.

---

### Phase 3 – Fact Modeling

• Built optimized Fact tables.

• Combined yearly datasets.

• Connected dimensions with fact tables.

• Validated totals after each transformation.

---

### Phase 4 – Model Optimization

• Removed unused tables.

• Hid staging queries.

• Optimized relationships.

• Applied Row-Level Security (RLS) preparation.

• Performed final validation.

---

## ⭐ Data Modeling Best Practices

• Designed a Star Schema.

• Maintained one-to-many relationships.

• Separated Fact and Dimension tables.

• Used surrogate keys.

• Optimized Power Query transformations.

• Removed unnecessary columns.

• Standardized table and column names.

• Improved model performance.

---

## 📈 Key Data Modeling Concepts

• Star Schema Design

• Fact & Dimension Modeling

• Table Granularity

• Merge & Append Operations

• Relationship Cardinality

• Left Join Strategy

• Data Cleansing

• Semantic Modeling

• Performance Optimization

---

## 📊 Model Features

• Clean Star Schema

• Optimized Relationships

• Reduced Model Size

• High Query Performance

• Business-Friendly Naming

• Analytics-Ready Data Model

---

## 📁 Repository Structure

```text
PowerBI-DataModel/
│
├── Data/
│   └── Raw Dataset
│
├── Images/
│   ├── Data_Model.png
│   ├── Star_Schema.png
│   └── Dashboard.png
│
├── PowerBI/
│   └── DataModel.pbix
│
└── README.md
```

---

## 📸 Screenshots

## 📸 Data Model

![Data Model](Snapshot/Snapshot%20of%20Data%20Model.png)

---

## ⭐ Star Schema

![Star Schema](Snapshot/Snapshot%20of%20Star%20Schema.png)

---

## 🚀 How to Use

• Clone the repository.

• Open the `.pbix` file in Power BI Desktop.

• Refresh the data if required.

• Explore the data model.

• Analyze the dashboards.


