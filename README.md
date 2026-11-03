# Logistics Operations Performance & Efficiency Analysis

**A Power BI Data Analytics Project**

## Project Overview

This project focuses on analysing logistics operations using Microsoft Power BI. It explores key areas of operational performance, driver and fleet efficiency, fuel consumption, operating costs, delivery performance and customer service.

The goal is to transform operational data into meaningful insights that can help stakeholders monitor business performance, identify operational inefficiencies and make informed decisions.

The project involves data preparation, data cleaning, data modelling, DAX calculations and interactive dashboard development.
### Tools & Technologies
- Microsoft Power BI
  - Power Query for data cleaning and transformation
  - DAX for measures and calculations
  - Data Modelling for establishing relationships between tables
  - Interactive visualisations for performance monitoring
## Business Problem

Logistics companies manage several operational activities, including transportation, driver performance, fuel consumption, delivery schedules and operating costs.

Without a clear view of these activities, management may find it difficult to monitor operational performance, identify inefficiencies, control costs and evaluate delivery reliability.

This project addresses the need for a centralised performance monitoring solution by using Power BI to analyse logistics data and present key operational metrics through interactive dashboards.

## 🎯 Business Goal

The goal of this project was to develop an interactive Logistics Operations Performance Dashboard using Microsoft Power BI to provide a comprehensive view of logistics activities.

The dashboard was designed to help management:

- Monitor overall logistics operational performance.
- Evaluate driver and fleet performance.
- Analyse fuel consumption and operating costs.
- Track delivery performance and service reliability.
- Identify operational inefficiencies and areas for improvement.
- Support data-driven decision-making through interactive visualisations.

## ❓ Business Questions

This project was designed to answer the following business questions:

### 1. Executive Operations Overview
- What is the overall operational performance of the logistics business?
- What is the total revenue generated?
- How many trips were completed?
- What is the total distance covered?
- What percentage of deliveries were completed on time?
- How does operational performance change over time?

### 2. Drivers & Fleet Performance
- Which drivers generate the highest revenue?
- Which drivers complete the highest number of trips?
- How efficient are drivers in terms of fuel consumption and idle hours?
- Which trucks generate the highest revenue?
- How does driver performance vary across the reporting period?

### 3. Operational Efficiency & Cost
- How much fuel is consumed across operations?
- What is the total fuel cost?
- How does fuel consumption change over time?
- What is the relationship between distance travelled and fuel consumption?
- Which trucks demonstrate better fuel efficiency?
- What is the fuel cost per mile?

### 4. Delivery & Customer Performance
- What percentage of deliveries are completed on time?
- How does on-time delivery performance change over time?
- Which customers account for the highest logistics activity or revenue?
- Are there differences in delivery performance across customers?
- What areas require improvement to enhance service reliability?

## 📂 Dataset Description

The logistics dataset consists of 14 CSV files containing operational information related to customers, drivers, fleet activities, facilities, trips, revenue, fuel consumption and delivery performance.

## 📊 Data Dictionary

The logistics dataset contains 14 related tables. Each table provides information about a specific area of the business and supports the analysis of logistics operations.

The following tables and columns have been identified so far:

| Table | Description | Key Columns |
|---|---|---|
| Customers | Contains customer-related information. | To be verified |
| Drivers | Stores driver details, employment information and experience. | driver_id, first_name, last_name, hire_date, termination_date, employment_status, cdl_class, years_experience |
| Driver Monthly Metrics | Contains monthly driver performance and operational metrics. | driver_id, month, trips_completed, total_miles, total_revenue, average_mpg, total_fuel_gallons, on_time_delivery_rate, average_idle_hours |
| Facilities | Contains information about logistics facilities and locations. | To be verified |

The remaining tables and their columns will be documented after reviewing the Power BI data model to ensure accuracy.

The datasets were imported into Microsoft Power BI, where Power Query was used for data preparation and transformation. The tables were then organised within the Power BI data model to support analysis across different areas of logistics operations.

The dataset provides the foundation for evaluating operational performance, driver productivity, fleet efficiency, fuel consumption, operating costs and delivery performance.

