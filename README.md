# Superstore Sales Data Pipeline & Executive Dashboard

## Project Overview
This project demonstrates an automated, end-to-end data pipeline designed to eliminate manual data aggregation tasks. Built entirely within Microsoft Excel using **Power Query (M Language)** and **Advanced Pivot Tables**, the model dynamically extracts data from fragmented monthly sales files, executes automated data-cleaning steps, and structures a centralized master table to power an interactive analytics dashboard.

## Key Features & Technical Workflow

### 1. Automated ETL Ingestion (Power Query)
* **Extraction**: Automatically scans a designated file directory to identify and ingest separate monthly Superstore data payloads.
* **Transformation & Schema Standardization**: Normalizes disparate column structures, enforces correct data types (Dates, Currency, Text), and cleans up formatting inconsistencies.
* **Time-Series Enrichment**: Programmatically derives and injects granular time dimensions (**Month** and **Year** columns) from the raw dates to support robust historical trend filtering.
* **Consolidation**: Stacks and appends all monthly transactional files into a single, highly optimized master dataset.

### 2. Multi-Dimensional Data Analysis (Pivot Tables)
* Engineered a collection of structural **Pivot Tables** to segregate and cross-examine performance across multiple business dimensions, including regional performance, temporal trends, and category performance.

### 3. Interactive Executive Dashboard
* Consolidated core business metrics into a central **Dashboard** tab.
* Coupled custom **Pivot Charts** with dynamic user-interactive **Slicers** to allow stakeholders to drill down into year-over-year growth and operational insights seamlessly at a single glance.

## Skills Demonstrated
* **Advanced Power Query & M Language** (Data Cleaning, Columns Transformation, Table Appending)
* **Data Modeling & Feature Engineering** (Extracting Time Dimensions, Schema Structuring)
* **Data Visualization & Dashboard Design** (Pivot Charts, Dynamic Slicers, UI Layout)
