# Data Observability & Quality Dashboard

*Developed by Ritu Raj Singh*

## Project Overview

This project focuses on monitoring data observability, metric performance, data freshness, and data quality across different source systems.

The dashboard provides a single view of important metrics such as total records, metric values, freshness, null records, duplicate records, and alert status.

## Objective

The main objective is to create a consistent metric and data-quality monitoring view that helps identify freshness issues, null values, duplicate records, and alert conditions.

## Data Preparation

The raw dataset was *cleaned and prepared in Microsoft Excel* before analysis and visualization.

The cleaning process included checking missing values, duplicate records, inconsistent text values, data types, and overall data quality.

*Excel was used for data cleaning. Python and Google Colab were used for analysis, not for the primary data-cleaning process.*

## Analysis

Python was used in Google Colab for exploratory analysis and to calculate key business and data-quality metrics.

The analysis included:

* Dataset overview
* Metric-level analysis
* Source-system analysis
* Freshness analysis
* Null and duplicate analysis
* Alert-rate analysis
* Status analysis
* Overall data-quality insights

## Tableau Dashboard

The final dashboard was created in Tableau using the cleaned dataset.

### Dashboard Components

* KPI Summary
* Metric Performance
* Source System Freshness
* Data Quality Issues
* Freshness Trend
* Quality Status Overview

### Key Metrics

* Total Records
* Total Metric Value
* Average Freshness
* Alert Rate
* Null Count
* Duplicate Count

## Tools & Technologies

* Microsoft Excel
* Python
* Pandas
* NumPy
* Google Colab
* Tableau
* GitHub

## Project Workflow

*Raw Data → Excel Cleaning → Clean Dataset → Python Analysis → Tableau Dashboard → GitHub*

## Outcome

The project provides a structured monitoring view for metric performance and data quality. It helps users identify freshness problems, data-quality issues, and alert conditions from a centralized dashboard.

## Conclusion

This project demonstrates an end-to-end data analytics workflow covering data preparation, exploratory analysis, metric monitoring, data-quality analysis, and interactive Tableau visualization.
