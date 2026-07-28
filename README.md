📊 Power BI Data Modeling Project

📌 Overview

  This project demonstrates the complete process of transforming a poorly designed Power BI data model into a clean, scalable, and high-performance Star Schema      suitable for analytics and reporting.

The project focuses on identifying fact and dimension tables, cleaning and restructuring raw data, applying data modeling best practices, and creating an optimized semantic model for Power BI dashboards.

🎯 Project Objectives

Transform an unstructured data model into a Star Schema

Improve report performance by optimizing relationships

Eliminate duplicate and unnecessary data

Build reusable Dimension and Fact tables

Apply consistent naming conventions and modeling standards

Prepare the model for scalable business reporting

🛠️ Technologies Used

Power BI Desktop

Power Query (M Language)

Data Modeling

DAX

Star Schema Design

Relationship Management


📂 Dataset Overview

The dataset simulates a real-world business environment containing multiple operational tables such as:

Customers

Products

Orders

Order Line Items

Invoices

Invoice Lines

Payments

Inventory

Shipments

Marketing Campaigns

Exchange Rates

Sales Targets

Security Tables


The raw model intentionally contains:

Many-to-many relationships
Duplicate tables
Poor naming conventions
Redundant columns
Mixed granularities
Non-optimized relationships
🏗️ Data Modeling Process

The project follows a structured four-phase approach:

Phase 1 – Data Exploration
Understand business entities
Analyze table granularity
Identify Fact and Dimension candidates
Review existing relationships
Phase 2 – Dimension Modeling

Created clean dimension tables by merging and transforming related datasets.

Example dimensions:

Dim Customer
Dim Product
Geography Attributes

Activities performed:

Merge related tables
Remove duplicates
Remove unnecessary columns
Rename columns
Standardize naming conventions
Create surrogate keys where required
Phase 3 – Fact Modeling

Built optimized fact tables from transactional datasets.

Examples:

Fact Orders
Fact Invoice
Fact Payments
Fact Campaign

Activities:

Append yearly datasets
Preserve transaction granularity
Connect facts to dimensions
Validate totals after every transformation
Phase 4 – Model Optimization

Final improvements included:

Remove unused tables
Hide staging tables
Optimize relationships
Apply naming standards
Prepare for Row-Level Security (RLS)
Validate business metrics
⭐ Data Modeling Best Practices Applied
✔ Star Schema Architecture
✔ One-to-Many Relationships
✔ Fact & Dimension Separation
✔ Surrogate Keys
✔ Power Query Transformations
✔ Column Optimization
✔ Relationship Validation
✔ Data Quality Checks
✔ Consistent Naming Convention
✔ Performance Optimization
📈 Key Data Modeling Concepts

This project demonstrates:

Star Schema Design
Fact Table Identification
Dimension Table Creation
Table Granularity Analysis
Merge & Append Operations
Surrogate Key Generation
Relationship Cardinality
Left Join Strategy
Data Cleansing
Performance Optimization
Semantic Model Design
📊 Model Features
Clean Star Schema
Optimized Relationships
Reduced Model Size
High Query Performance
Business-Friendly Table Names
Standardized Columns
Analytics-Ready Data Model
📁 Repository Structure
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
📸 Screenshots
Data Model

(Add your Data Model screenshot here.)

Star Schema

(Add the optimized Star Schema screenshot.)

Dashboard

(Add your dashboard screenshot if available.)

🚀 How to Use
Clone the repository.
Open the .pbix file in Power BI Desktop.
Refresh the data if required.
Explore the data model.
Analyze the relationships and dashboards.
📚 Learning Outcomes

Through this project, I gained practical experience in:

Designing scalable Power BI data models
Building Star Schema architectures
Creating optimized dimension and fact tables
Applying Power Query transformations
Understanding data granularity
Managing relationships and cardinality
Improving Power BI model performance
Following enterprise data modeling standards
👨‍💻 Author

