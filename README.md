# Big Data Analytics – Electronica 2025

## Objective
Design of a scalable Big Data architecture integrating production, finance and social media data to enable KPI-driven production optimization and data-based decision-making.

---

## Business Problem
- Manual Excel-based reporting (error-prone and fragmented)
- Production failures recorded but not systematically analyzed
- No integration between production, finance and sales data
- Lack of a Single Source of Truth

---

## My Contribution
- Designed the Big Data architecture concept
- Structured heterogeneous data sources into an integrated model
- Conducted KPI analysis (Revenue, Cost, Profit 2012–2021)
- Performed Pareto analysis on production failures
- Identified operational and margin optimization potential
- Developed strategic improvement recommendations

---

## Data Sources
- Production systems (machine logs, error types)
- Financial & sales data (revenue, cost, profit)
- Customer data
- Conceptual integration of social media (Twitter)

---

## Architecture Overview
ETL / Streaming → Hadoop → HDFS → Hive → SQL Queries → BI Dashboard

See `architecture-diagram.png` for visualization.

---

## Analytical Focus

### 1. KPI Monitoring
- Revenue development
- Cost trends
- Profit evolution
- Customer class revenue distribution

### 2. Failure Analysis
- Top machine failures (2020–2021)
- Failure distribution by product category
- Identification of dominant error types

### 3. Pareto Analysis
- ~20% of error types responsible for ~80% of losses
- Quality assurance weaknesses identified as key driver

---

## Business Impact
- Clear identification of production inefficiencies
- Prioritization of high-impact failure types
- Strategic recommendation for early QA checks
- Margin-focused portfolio optimization
- Concept for predictive maintenance & real-time monitoring

---

## Technologies & Concepts
- SQL (analysis logic)
- Big Data architecture (Hadoop ecosystem – conceptual)
- Data validation techniques
- KPI-based reporting
- Pareto principle application

---

## Documentation
Full project presentation available in `project-overview.pdf`.

---

## Author
Amna Yasar Goraya
