# SmogSense_Karachi_Air_Quality
Project Overview

SmogSense is an exploratory data analysis project that examines daily PM2.5 air-quality measurements in Karachi, Pakistan, from October 2016 to December 2024. The goal is to identify monthly and yearly pollution patterns using Python data-analysis and visualization tools.

Objectives

- Inspect and assess the quality of air-quality data.
- Analyze monthly and annual average PM2.5 concentrations.
- Visualize pollution patterns over time.
- Identify missing readings and document limitations.

Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook in Visual Studio Code

Key Findings

- Highest average monthly concentration: December — 90.24 µg/m³.
- Lowest average monthly concentration: August — 25.472 µg/m³.
- Highest annual average: 2021 — 58.19 µg/m³.
- Lowest annual average: 2019 — 37.75 µg/m³.
- Six PM2.5 readings were missing, all in 2023.
- No duplicate rows or negative PM2.5 readings were found during the data-quality checks.

Methods

The project includes date conversion, feature extraction for year and month, missing-value checks, duplicate and negative-value checks, grouping and aggregation with Pandas, and visualizations using Matplotlib and Seaborn.

Limitations

- Missing readings may influence monthly and annual comparisons.
- Missing PM2.5 values were left unchanged rather than imputed.
- The analysis identifies patterns in the available data; it does not establish the causes of pollution changes.
- Results depend on the coverage and quality of the source measurements.

Dataset

Source: "PAQI — Unveiling Karachi Air" (https://github.com/PakAirQuality/Unveiling-Karachi-Air)

The analysis uses daily PM2.5 measurements from the source dataset. Refer to the original repository for dataset details and usage terms.

How to Run

1. Download or place the dataset in the project folder.
2. Open the ".ipynb" notebook in Visual Studio Code.
3. Ensure Python and the required libraries are installed.
4. Run all notebook cells from top to bottom.

Author

A Computer Science student interested in data science and AI applications for real-world problems.
