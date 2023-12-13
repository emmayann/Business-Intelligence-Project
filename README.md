# Business Intelligence Project

Overview
This project is a comprehensive data integration and dimensional modeling pipeline designed to transform and load relational data from [Source Database] to a dimensional database for enhanced analytics and reporting. The project focuses on maintaining historical data using Slowly Changing Dimensions (SCD) techniques. The project also includes a PowerBi Dashboard with some visualizations of analysis. 

Key Features
Data Integration: Efficiently extracts data from the [Source Database] and transforms it into a dimensional model.
SCD Strategies: Implements Slowly Changing Dimensions to manage historical changes in the data.
Merge Operations: Utilizes SQL MERGE statements for upserts, updates, and deletions.
Python Implementation: The entire pipeline is implemented using Python, providing flexibility, readability, and ease of maintenance.
Configurability: Easily customizable configurations for various database connections and pipeline parameters.
Project Structure
Pipeline Components: The project consists of modular tasks for data extraction, transformation, and loading.
SCD Implementation: [Describe any specific SCD implementation details, e.g., Type 1, Type 2, etc.]
Database Schema: Clearly defined dimensional database schema with primary and foreign key relationships.
