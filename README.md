## Cricket T20 Analysis using Python and Power BI

# Table of Contents :
 - Introduction
 - Project Overview
 - Features
 - Installation
 - Data Collection
 - Data Transformation
 - Power BI Dashboard
 - Usage
 - Acknowledgements

# Introduction :
This project aims to analyze T20 cricket matches by utilizing Python for data processing and transformation, and Power BI for creating an interactive and visually appealing dashboard. The analysis covers various aspects such as player performance, team statistics, match summaries, and more.

# Project Overview :
The project consists of two main components:

 - Data Transformation using Python: Loading, transforming, and saving data from multiple JSON files into CSV files.

 - Dashboard Creation using Power BI: Using the transformed data to create an interactive dashboard with DAX measures for detailed insights.

# Features :
 - Load and preprocess T20 cricket match data from JSON files.
 - Transform and save the data into CSV files.
 - Analyze data using Power BI, leveraging DAX measures for advanced insights.
 - Create an interactive and visually pleasing dashboard.

# Installation :
- Prerequisites
  - Python 3.x
  - Power BI Desktop
  - Python Libraries
Install the required Python libraries using pip

# Data Collection :
The data is collected from multiple JSON files covering various aspects such as bowling, batting, match summaries, and player information. 
These files are included in the "DataDirectory/Dataset_cricket"  directory of the repository.
  
# Data Transformation :
The data transformation is performed using Python, where data from JSON files is loaded, cleaned, and saved into CSV files for further analysis in Power BI.

For detailed code, refer to the "Cricket_T20_EDA.ipynb" file in the repository.

# Steps :
 - Load data from JSON files.
 - Convert JSON data to Pandas DataFrames.
 - Clean and transform the data.
 - Save transformed data to CSV files located in the DataDirectory/cricket_t20_csv directory.

# Power BI Dashboard :
 # Steps to Create Dashboard :
  - Import CSV Files into Power BI: Load the transformed CSV files into Power BI.
 - Data Modeling: Establish relationships between different tables as needed.
  - Create DAX Measures: Define DAX measures to perform advanced calculations.
  - Build Visualizations: Use Power BI’s visualization tools to create charts, graphs, and other visual elements.
  - Interactive Dashboard: Add slicers and filters for interactivity.

# Usage :
 - Run Python Transformation: Execute the Python script to transform the JSON data and save it as CSV files.
 - Load Data into Power BI: Import the CSV files into Power BI.
 - Create and Customize Dashboard: Follow the outlined steps to build and customize the Power BI dashboard.
 - Explore Insights: Use the interactive features of the dashboard to explore and interpret the data.

# Acknowledgements :
 - Data sources for providing cricket statistics.
 - The Python community for developing powerful libraries.
 - Microsoft for Power BI.
