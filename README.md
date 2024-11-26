# GHCN-Data-Analysis-using-Spark
Project Title: Exploring and Analyzing Climate Data from the Global Historical Climate Network (GHCN)
Description
This repository contains a comprehensive analysis of climate data from the Global Historical Climate Network (GHCN). The project leverages Apache Spark for distributed computing and Tableau for visualizations to handle and interpret a vast dataset spanning over 250 years (1750–2024). The dataset includes metadata about global weather stations and daily climate summaries, comprising over 3 billion observations.

Key Features
Data Enrichment: Joined metadata tables, such as stations, inventory, countries, and states, to create a consolidated enriched metadata table.
Scalable Data Analysis: Processed over 100 GB of climate data using Spark's distributed computing capabilities.
Insights Generation:
Explored geographical distributions of 125,983 weather stations, identifying operational and inactive stations.
Calculated average precipitation and temperature metrics globally, with specific analyses for New Zealand.
Detected and flagged anomalies, such as unusually high rainfall in certain regions.
Visualizations: Created interactive time series and geographical maps using Tableau to communicate key findings effectively.
Tools and Technologies
Apache Spark for data preprocessing and distributed computation.
Tableau for visualization of climate trends and anomalies.
Python and PySpark for scripting and data transformation.
Haversine formula to calculate distances between geographical points.
Highlights
The dataset's scale and complexity required advanced preprocessing, including handling compressed data and optimizing Spark configurations for efficient task execution.
Analyzed temporal and spatial patterns in temperature and precipitation, providing insights into global and regional climate variations.
Identified potential data quality issues in precipitation records for specific countries, prompting further investigation.
This project demonstrates scalable data analysis techniques for large datasets, offering a roadmap for similar analyses in environmental science, meteorology, and data engineering domains.phase of the assignment involved analysing the daily data and visualizing key findings. Given that the daily data comprised approximately 250 compressed CSV files, loading and analysing them required significant time and computational resources. All daily data from the beginning was integrated with the enriched stations table, examined in accordance with the assignment's questions, and the results were recorded.

All the preprocessing and analysis were conducted using the Apache Spark distributed computing framework, where the allocation of resources, creation of partitions, and task assignments for each stage were also explored. For the majority of the visualizations, Tableau software was utilized. Additionally, Python coding, grammar corrections, and other information were supported by ChatGPT (OpenAI, 2024), Stack Overflow (Stack Exchange Inc;, 2024), and Quill Bot (QuillBot, 2024).
