# Data-Modelling-and-Warehouse-Creation
# Data Modelling and Warehouse Creation in Snowflake

## Overview

This project demonstrates the process of data modelling and warehouse creation in Snowflake. It covers the steps taken to design a data model and set up an x-small Snowflake warehouse using only the Snowflake Web UI to support analytics and reporting requirements. Draw.io was used for drawing the conceptual, logical, and physical data models.

## Table of Contents

1. Prerequisites
2. Data Modelling
3. Warehouse Creation
4. Conclusion

## Prerequisites

- Snowflake account
- Basic SQL knowledge
- Draw.io account

## Data Modelling

### 1. Data Analysis

- Identified the business requirements and data sources.
- Performed data profiling to understand the structure and quality of the data.

### 2. Conceptual Data Model

- Defined high-level entities, attributes, and relationships using Draw.io.
- Created an ER diagram to visualize the conceptual model.
  
- ![alt text](<conceptual model.png>)

### 3. Logical Data Model

- Transformed the conceptual model into a logical model using Draw.io.
- Defined tables, columns, primary keys, and foreign keys.

![alt text](<logical model.png>)

### 4. Physical Data Model

- Created the physical schema in Snowflake using the Snowflake Web UI.
- Implemented normalization and denormalization techniques as per the requirements.
- Used Draw.io to visualize the physical data model.

## Warehouse Creation

### 1. Snowflake Account Setup

- Created a Snowflake account and logged in using the Snowflake Web UI.

### 2. Warehouse Configuration

- **Warehouse Size**: Set the warehouse size to x-small using the Snowflake Web UI.
- Configured auto-suspend and auto-resume settings to optimize costs.

### 3. Role and Permission Management

- Created roles and assigned the necessary permissions to access the data warehouse using the Snowflake Web UI.
- Implemented role-based access control (RBAC) to restrict unauthorized access.

### 4. Loading Data

- Loaded the data into the Snowflake tables using the Snowflake Web UI.

### 5. Query Performance Tuning

- Optimized SQL queries using Snowflake Query Profile available in the Snowflake Web UI.
- Monitored warehouse utilization and adjusted the configuration as needed using the Snowflake Web UI.

## Conclusion

This project provides a comprehensive guide to data modelling and warehouse creation in Snowflake using only the Snowflake Web UI and Draw.io for drawing the conceptual, logical, and physical data models. By following the steps outlined above, you can design an efficient data model and set up an x-small Snowflake warehouse to meet your organization's analytical needs.
