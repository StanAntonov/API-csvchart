# Fastmarkets API Data Pipeline

A Python-based ETL pipeline that extracts commodity pricing data from the Fastmarkets API, transforms it into structured format, and generates analytical visualizations.

## Project Overview

This project demonstrates a complete data engineering workflow:
- Authenticates with the Fastmarkets API using service credentials
- Extracts instrument metadata and historical price data
- Transforms nested JSON responses into structured tables
- Exports cleaned data to CSV format
- Generates price fluctuation charts for analysis

## Features

- Secure API authentication with bearer tokens
- Data extraction from multiple endpoints
- JSON to structured data transformation using pandas
- Data type validation and cleaning
- Automated CSV export with proper file handling
- Price trend visualization with matplotlib
- Comprehensive error handling and logging

## Technologies Used

- Python 3.x
- Requests (API calls)
- Pandas (Data transformation)
- Matplotlib (Data visualization)
- OS (File system operations)
