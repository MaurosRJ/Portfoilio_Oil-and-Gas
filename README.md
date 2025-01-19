# Oil and Gas Well Data Analysis - A New York case study

## Overview
This project focuses on analyzing historical oil and gas well data in New York to uncover trends, improve data insights, and support decision-making in the energy sector. By examining well attributes, statuses, and production patterns, the analysis aims to provide actionable insights for optimizing operations and policy development.

## Objectives
- Analyze historical oil, gas, and other regulated well data to identify key trends and patterns.
- Investigate the well statuses (e.g., active, inactive) and their implications on production efficiency.
- Handle missing data and ensure the dataset's integrity for reliable analysis.
- Create visualizations to present findings clearly and effectively.

## Dataset
- **Source**: Kaggle: Historical oil and gas well data in New York (titled: `oil-gas-other-regulated-wells-beginning-1860`).
- **Time Range**: 1870 to 2018, with the analysis focusing on entries up to the early 1950s.
- **Features**:
  - Well ID
  - Location (latitude, longitude)
  - Well Type (e.g., oil, gas, other regulated)
  - Status (e.g., active, inactive)
  - Production Metrics (if available)
  - Installation and Decommission Dates
  - Additional Attributes (e.g., depth, operator)

## Methodology
1. **Data Cleaning and Preprocessing**:
   - Handled missing values and inconsistencies in the dataset.
   - Standardized well statuses for clear categorization.
   - Filtered and validated data for the New York region.

2. **Exploratory Data Analysis (EDA)**:
   - Assessed well distribution across New York using geospatial mapping.
   - Analyzed the correlation between well attributes (e.g., depth, type) and production activity.
   - Identified historical trends in well installations and status transitions.

3. **Visualization and Insights**:
   - Created visualizations such as box plots, time-series charts, and geospatial maps to illustrate findings.
   - Highlighted inactive wells and areas for potential reactivation or remediation.

## Tools and Technologies
- **Programming Languages**: Python (Pandas, NumPy, Matplotlib, Seaborn)
- **Data Visualization**: Power BI
- **Geospatial Analysis**: Folium, Geopandas
- **Data Storage and Management**: SQL, CSV format

## Results
- Identified percentage of active wells, with a significant portion of inactive wells concentrated in specific regions.
- Highlighted trends in well installations, with peak plugged wells activity occurring between 1965 -1993 according to data.
- Provided recommendations for prioritizing well reactivations based on production potential and geographical considerations.

## Challenges and Solutions
- **Handling Missing Data**: Imputed missing values and used domain knowledge to fill gaps where possible.
- **Dataset Size**: Optimized processing by filtering data for the most relevant time period and region.

## Future Work
- Extend analysis to include post-1950s data for more comprehensive insights.
- Incorporate additional datasets, such as production metrics and environmental impact data.
- Develop predictive models to forecast well productivity and identify high-potential regions for future exploration.
