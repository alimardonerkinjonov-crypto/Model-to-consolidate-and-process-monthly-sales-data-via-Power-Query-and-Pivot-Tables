# Superstore Sales Data Pipeline & Executive Dashboard

## Overview
An automated, end-to-end data pipeline and interactive executive dashboard built entirely within Microsoft Excel. The solution eliminates manual data aggregation by leveraging Power Query (M Language) to dynamically extract, clean, and consolidate fragmented monthly sales files into a centralized master dataset — powering a fully interactive analytics dashboard.

---

## Technical Workflow

### 1. Automated ETL Ingestion (Power Query)
- **Extraction:** Automatically scans a designated directory to identify and ingest separate monthly Superstore data payloads
- **Transformation:** Normalizes disparate column structures, enforces correct data types (Dates, Currency, Text), and resolves formatting inconsistencies
- **Time-Series Enrichment:** Programmatically derives Month and Year dimensions from raw date fields to support granular historical filtering
- **Consolidation:** Appends all monthly transactional files into a single optimized master dataset

### 2. Multi-Dimensional Analysis (Pivot Tables)
- Engineered structured Pivot Tables to cross-examine performance across regional, temporal, and category dimensions

### 3. Interactive Executive Dashboard
- Centralized core business KPIs into a single Dashboard view
- Integrated dynamic Slicers with custom Pivot Charts to enable seamless year-over-year trend analysis and operational drill-down
- Implemented auxiliary helper tables with dynamic lookup formulas (INDEX/MATCH, HLOOKUP, COUNTA) to render a Grand Total trend line that intelligently suppresses overlap when a single category is in focus

## Skills Demonstrated
* **Advanced Power Query & M Language** (Data Cleaning, Columns Transformation, Table Appending)
* **Data Modeling & Feature Engineering** (Extracting Time Dimensions, Schema Structuring)
* **Data Visualization & Dashboard Design** (Pivot Charts, Dynamic Slicers, UI Layout)
* <img width="2481" height="1755" alt="Dashboard_page-0001" src="https://github.com/user-attachments/assets/de0546af-808b-4652-877b-36010db22359" />

