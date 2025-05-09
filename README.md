# Global Fashion Retail Sales SSAS and BI Project

## Overview

This project focuses on implementing an SSAS OLAP cube, demonstrating OLAP operations, and developing interactive Power BI reports using an existing data warehouse based on the **Global Fashion Retail Sales** dataset. It highlights multidimensional analysis, cube design, and business intelligence reporting.

---

## 📂 Project Folder Structure

```plaintext
SSAS-Global_Fashion_Sales-project/
├── Doc/                     # Documentation and reference images
├── Excel_Reports/           # Excel files with OLAP demonstrations
├── PowerBI_Reports/         # Power BI project files and reports
├── SSAS_Project/            # SSAS cube project files
├── .gitignore               # Git configuration
└── README.md                # Project description
```
## 📊 Data Source

- Global Fashion Retail Sales DW
- **Time Period:** 2024-01-01 to 2025-01-01  
- **Schema:** Snowflake schema (pre-built data warehouse in SSIS)

### Dimensions:
- Country
- Store
- Product Category
- Product Subcategory
- Product
- Customer
- Employee
- Transaction

### Fact Table:
- Captures sales activities and purchasing history

---

## 🏗️ SSAS Cube Implementation

![SSAS Cube Implementation](Doc/Global%20Fashion%20Retail%20Sales%20-DW(dsv).png)

- **Tool:** SQL Server Data Tools (SSDT)  
- **Type:** Analysis Services Multidimensional and Data Mining Project

### Steps:
1. Created data source
2. Created data source view with tables and relationships
3. Built cube using Cube Wizard
4. Configured hierarchies and dimensions
5. Deployed and processed the cube

---

## 🔍 OLAP Operations

Performed using Excel connected to SSAS cube:

- **Roll-up** → Aggregate to higher levels (e.g., product → category)  
- **Drill-down** → Explore detailed levels (e.g., year → quarter → month)  
- **Slice** → Apply filters  
- **Dice** → Analyze sub-cubes  
- **Pivot** → Rearrange dimensions

---

## 📈 Power BI Reports

Connected Power BI Desktop to SSAS cube (Import mode) and created interactive reports:

1. **Matrix Visual Report** → Tabular summaries with groupings  
2. **Report with Multiple Slicers** → Time-based filtering  
3. **Drill-Down Report** → Hierarchical exploration  
4. **Drill-Through Report** → Detailed pages linked from visuals

---

## 💻 Technologies

- SQL Server Data Tools (SSDT)  
- SQL Server Analysis Services (SSAS)  
- Microsoft Excel  
- Power BI Desktop & Service

---
