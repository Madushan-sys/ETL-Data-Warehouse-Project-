# ETL Process for Monthly Sales Summary Fact using Azure Data Factory

## Overview

This project demonstrates the implementation of an ETL process to create a monthly sales summary fact table using Azure SQL Database and Azure Data Factory (ADF). The steps include designing a target data warehouse, performing ETL operations from multiple data sources, populating a date dimension, scheduling ETL runs, and creating a monthly sales summary.

## Table of Contents

1. [Project Description](#project-description)
2. [Technologies Used](#technologies-used)
3. [Setup and Installation](#setup-and-installation)
4. [Implementation Details](#implementation-details)
    - [Target Data Warehouse](#target-data-warehouse)
    - [ETL Process](#etl-process)
    - [Date Dimension](#date-dimension)
    - [Scheduling](#scheduling)
    - [Monthly Sales Summary Fact](#monthly-sales-summary-fact)
5. [Contributors](#contributors)

## Project Description

This project involves the following tasks:

1. Implement the target data warehouse using Azure SQL Database.
2. Use Azure Data Factory to perform ETL from three data sources to the target data warehouse, applying necessary transformations.
3. Populate the date dimension for analysis from 2024-01-01 to 2024-05-24.
4. Schedule an ETL pipeline to run every 20 minutes until 2024-12-31.
5. Create ETLs for a monthly sales summary fact.

## Technologies Used

- Azure SQL Database
- Azure Data Factory
- SQL
- JSON
- CSV

## Setup and Installation

1. **Azure SQL Database**: Set up an Azure SQL Database instance.
2. **Azure Data Factory**: Create an Azure Data Factory instance.
3. **GitHub Repository**: Clone this repository to your local machine.

```bash
git clone https://github.com/Madushan-sys/ETL Data Warehouse Project.git
￼Enter
