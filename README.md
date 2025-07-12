# SQL-Data-Cleaning-and-Analysis-Global-Layoffs

# Project Overview
This project demonstrates comprehensive SQL data cleaning and exploratory data analysis (EDA) techniques using a dataset of corporate layoffs from 2022. The project showcases essential data analyst skills including data cleaning, standardization, duplicate removal, and statistical analysis to uncover meaningful insights about global layoff trends.

# Project Objectives
- Data Cleaning: Transform raw, messy data into a clean, analysis-ready dataset
- Data Standardization: Ensure consistency across all data fields
- Exploratory Analysis: Discover trends, patterns, and insights about global layoffs
- SQL Mastery: Demonstrate advanced SQL techniques and best practices

# Technical Skills Demonstrated
## Data Cleaning Techniques

- Duplicate Detection & Removal: Using ROW_NUMBER() window functions
- Data Standardization: Cleaning industry categories, country names, and date formats
- Null Value Handling: Strategic approach to missing data
- Data Type Conversion: Converting text dates to proper DATE format

## Advanced SQL Concepts

- Common Table Expressions (CTEs): For complex queries and data transformations
- Window Functions: ROW_NUMBER(), DENSE_RANK(), SUM() OVER()
- Aggregate Functions: SUM(), MAX(), MIN(), COUNT()
- String Functions: TRIM(), SUBSTRING(), STR_TO_DATE()
- Join Operations: Self-joins for data population
- Subqueries: Nested queries for advanced filtering


##  Key Insights Discovered

- **Largest Single Layoff**: Identified companies with highest single-day layoffs
- **Complete Shutdowns**: Companies with 100% layoffs (startup failures)
- **Geographic Hotspots**: Cities and countries most affected by layoffs
- **Industry Impact**: Technology sector heavily impacted
- **Temporal Trends**: Peak layoff periods during 2022
- **Rolling Analysis**: Month-over-month cumulative layoff trends

## Notable Findings

- **Meta (Facebook)** had one of the largest single layoff events
- **San Francisco Bay Area** was significantly impacted geographically
- **Consumer and Retail** industries showed high layoff volumes
- **Post-IPO companies** were particularly affected
- Clear seasonal patterns emerged in the layoff data

##  How to Run

1. **Setup Database**: Create a MySQL database named `world_layoffs`
2. **Import Data**: Load the raw layoffs dataset into `world_layoffs.layoffs` table
3. **Execute Cleaning**: Run the data cleaning SQL script first
4. **Run Analysis**: Execute the EDA script on the cleaned data
5. **Review Results**: Analyze outputs and visualize key metrics

## Tools & Technologies

- **Database**: MySQL
- **SQL Techniques**: Advanced querying, window functions, CTEs
- **Data Source**: Kaggle dataset
- **Development**: SQL script development and testing


## Business Impact

- **HR Professionals**: Understanding layoff trends and patterns
- **Investors**: Assessing market stability and company performance
- **Job Seekers**: Identifying stable industries and locations
- **Economists**: Analyzing labor market trends during economic uncertainty

