# Chicago Traffic Crash Analytics Dashboard

## Overview

The Chicago Traffic Crash Analytics Dashboard is a data analysis application developed using Python, SQL, Pandas, SQLite, and Streamlit. The project analyzes traffic crash records reported in the City of Chicago to identify patterns, trends, risk factors, and crash hotspots.

The dashboard provides insights into crash severity, injury trends, weather impacts, high-risk streets, time-based crash behavior, and geographic crash distributions.

## Dataset Information

Dataset Name: Chicago Traffic Crashes

Source: Chicago Data Portal

Format: CSV

Total Records: 600,000+ records

Time Range: 2015 to Present

Spatial Coverage: Chicago, Illinois, USA

License: Public Domain

Database: SQLite

## Technologies Used

* Python
* SQL
* SQLite
* Pandas
* Streamlit
* Matplotlib
* SQLAlchemy

## Features

### Crash Analysis

* Most common crash types
* Year-over-year crash growth analysis
* Crash trends across different conditions

### Injury Analysis

* Injury percentages by crash type
* Streets with the highest injury rates
* Injury comparison under different lighting conditions

### Weather Analysis

* Weather conditions associated with crashes
* Weather and crash type combinations
* Environmental impact assessment

### Time-Based Analysis

* Peak crash hours by month
* Night-time crash causes
* High-risk time slots
* Average crashes by day and hour

### Geographic Analysis

* Crash hotspot identification
* Location-based crash frequency analysis
* Geographic visualization using maps

### Advanced SQL Analytics

* Window functions using ROW_NUMBER()
* Growth trend analysis using LAG()
* Ranking top contributing crash causes

## Project Structure

* homepage.py – Dashboard home page
* guvi.py – Main Streamlit application
* traffic_crashes.db – SQLite database
* requirements.txt – Project dependencies

## Installation

Install the required packages:

pip install -r requirements.txt

Run the application:

streamlit run guvi.py

## Conclusion

This project demonstrates the use of SQL and Python for real-world traffic crash analysis. The dashboard helps identify high-risk locations, common crash causes, injury-prone conditions, and temporal crash patterns through interactive visualizations and analytical queries.

## Author

Sai Siddartha Reddy
