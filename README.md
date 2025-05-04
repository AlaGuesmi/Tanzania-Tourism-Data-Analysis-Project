# 🧭Tanzania Tourism Data Analysis Project

📄 **Overview**
This project focuses on analyzing **Tanzania dataset** containing tourism data collected from international visitors to Tanzania. It aims to uncover trends in travel preferences, spending patterns, and demographic behavior using data cleaning, transformation, and exploratory analysis techniques in Pandas and visualizations via Seaborn and Klib.

📁 **Dataset Description**

- The dataset contains 4,809 observations and 22 variables capturing detailed information on international tourists visiting Tanzania. Key variables include:

- country, age_group, travel_with, purpose

- tour_arrangement, total_cost, main_activity

- Package usage indicators (accommodation, food, insurance, etc.)

- Duration of stay on mainland and Zanzibar

- Payment method, and overall impression

🔍 **Project Workflow**

- Data Exploration

  Loaded and previewed the dataset:

  Inspected data types, dimensions, and descriptive statistics

- Data Cleaning

  Handled missing values using mode, mean, and most frequent values

  Dropped or filtered low-quality rows based on threshold logic

  Removed duplicate records to ensure data integrity

- Data Transformation:

  Used .map(), .replace(), and .apply() functions for feature standardization and transformation

- Grouped and aggregated data to identify:

  Most visited countries by expenditure

  Popular age groups and purposes

  Cost patterns by country, and many other insights

- Exploratory Data Analysis:

  Generated value counts for categorical insights

  Created correlation heatmaps using both Klib and Seaborn to examine numerical relationships

📌 **Key Insights**

- Identified the most and least common travel purposes per age group

- Determined which countries contribute most to Tanzania’s tourism revenue

- Found that independent travelers made up a significant portion of visitors

- Analyzed total costs, trip duration, and main activities to detect spending behavior

💾 **Output**

- Visualizations and grouped summaries for presentation

📎 **Tools & Libraries**

- Python, Pandas, NumPy

- Seaborn, Matplotlib, Klib
