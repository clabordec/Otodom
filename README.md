# Otodom

## Overview

**Otodom** is a real estate platform that connects property seekers with sellers and landlords. This repository serves as a comprehensive solution for extracting, transforming, and analyzing real estate data from the Otodom website ([https://www.otodom.pl](https://www.otodom.pl)). The insights derived from this project can support decision-making in areas such as market analysis, pricing strategies, and investment opportunities.

## Features
- **Data Scraping**: Extract property listings, pricing, and other key details from the Otodom website using Bright Data.
- **Data Transformation**: Process raw data with Python to ensure it is clean, structured, and ready for analysis.
- **Data Storage and Analysis**: Load data into Snowflake for advanced querying and analytical processing.
- **Business Intelligence**: Perform additional transformations and visualizations using Excel to generate actionable insights.

---

## Tools and Technologies

### 1. **Bright Data**
- A robust proxy and scraping solution used to extract structured and unstructured data from the Otodom website.
- Automates data collection processes with high efficiency and minimal disruption.

### 2. **Python**
- Used for cleaning, preprocessing, and transforming scraped data.
- Libraries used include:
  - `pandas`: Data manipulation and cleaning.
  - `numpy`: Numerical computations.
  - `beautifulsoup4` and `selenium`: For web scraping.
  - `requests`: Handling HTTP requests.

### 3. **Snowflake**
- Cloud-based data warehouse used for storing and analyzing large volumes of real estate data.
- Supports advanced SQL queries for business intelligence and predictive modeling.

### 4. **Excel**
- Used for additional data transformation and creating clear, actionable reports.
- Provides pivot tables, charting, and dashboard capabilities for visualizing trends and insights.

---

## Workflow

### 1. **Data Collection**
- Use Bright Data to scrape real estate listings, including:
  - Property type (e.g., apartment, house, commercial).
  - Location details.
  - Price, size, and additional features.
- Schedule automated scraping jobs to ensure data freshness.

### 2. **Data Transformation**
- Clean and preprocess data using Python.
  - Handle missing values, duplicates, and inconsistent formatting.
  - Convert raw data into structured formats (CSV, JSON).

### 3. **Data Storage**
- Load the processed data into Snowflake for centralized storage.
- Ensure data integrity and scalability for future analytical needs.

### 4. **Data Analysis**
- Query the data in Snowflake to derive key metrics, such as:
  - Average property prices per location.
  - Trends in real estate demand over time.
  - Distribution of property types.

### 5. **Business Intelligence**
- Use Excel for advanced transformations and to create dynamic dashboards.
- Generate visualizations such as:
  - Heatmaps for property demand.
  - Price trends across regions.
  - Comparison of rental vs. sale markets.

---

## Deliverables
- **Data Insights**: Comprehensive reports on real estate market trends.
- **Dynamic Dashboards**: Interactive Excel dashboards for stakeholders.
- **Scalable Solution**: Reusable pipeline for ongoing data collection and analysis.

---

## Contact
For inquiries, feedback, or support, please contact:
- **Name**: Chaanyah Laborde
- **Email**: chaanyahlaborde@gmail.com
- **LinkedIN**: [claborde](https://www.linkedin.com/in/claborde/)

