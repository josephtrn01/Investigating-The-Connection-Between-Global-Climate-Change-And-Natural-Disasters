
# Investigating the Connection Between Global Climate Change and Natural Disasters

![Python](https://img.shields.io/badge/Python-Data%20Analysis-3776AB?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Processing-150458?logo=pandas&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-Visualization-F2C811?logo=powerbi&logoColor=black)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

## Project Overview

This project investigates the relationship between **global climate change and natural disasters** by analyzing historical temperature anomalies, atmospheric CO₂ concentrations, disaster frequency, and socioeconomic indicators.

Using **Python for data acquisition, cleaning, integration, and exploratory analysis**, alongside **Power BI for interactive data visualization**, the project examines how climate trends relate to natural disaster patterns across different countries and economic conditions.

The goal is to identify long-term environmental trends, geographic vulnerabilities, and socioeconomic disparities to support data-driven climate resilience and disaster preparedness strategies.

## Technologies Used

- **Programming Language:** Python
- **Data Processing:** Pandas, NumPy
- **Data Visualization:** Power BI, Matplotlib, Seaborn
- **Development Environment:** Jupyter Notebook
- **Analytical Techniques:** Time-Series Analysis, Exploratory Data Analysis (EDA), Data Integration, Geospatial Analysis
- **Feature Engineering:** Disasters per Million Population, GDP Quartile Classification

## Data Sources

The project integrates four major global datasets:

| Data Source | Description |
|---|---|
| **NASA GISTEMP** | Global temperature anomalies |
| **NOAA** | Atmospheric CO₂ concentrations |
| **EM-DAT** | Natural disaster frequency, types, and impacts |
| **World Bank** | GDP, population, and socioeconomic indicators |

These datasets were cleaned, standardized, and merged using **year and ISO country codes** to enable cross-country and historical comparisons.

## Project Workflow

1. **Data Acquisition:** Collect historical climate, disaster, and socioeconomic datasets.
2. **Data Preprocessing:** Handle missing values, standardize dates, and clean country identifiers.
3. **Data Integration:** Merge datasets using Python Pandas.
4. **Feature Engineering:** Calculate disasters per million people and categorize countries by GDP quartiles.
5. **Exploratory Data Analysis:** Examine climate trends, disaster frequency, and economic vulnerability.
6. **Data Visualization:** Develop Power BI dashboards featuring time-series charts, geographic maps, and interactive filters.

## Key Findings

- **Rising Global Temperatures:** Atmospheric CO₂ concentrations and global temperature anomalies show strong upward trends, particularly since the 1980s.
- **Increasing Disaster Reports:** Recorded natural disaster events increased substantially between 1960 and 2023, although improved reporting may contribute to this trend.
- **Climate and Disaster Trends:** Temperature anomalies and reported disaster frequency exhibit overlapping long-term increases, suggesting relationships worth further investigation.
- **Geographic Vulnerability:** Countries such as China, India, Indonesia, and the United States recorded high numbers of natural disasters.
- **Disproportionate Disaster Burden:** Small island states and territories, including Tuvalu and Palau, experienced particularly high disaster rates relative to their populations.

## Data Visualizations

The project includes several analytical visualizations:

- Global Average Disasters per Million People Over Time
- Total Natural Disasters Reported Globally (1960–2023)
- Global CO₂ Concentrations vs. Temperature Anomalies
- Disaster Frequency vs. Global Temperature Anomalies
- Geographic Distribution of Natural Disasters
- Top 10 Countries with the Highest Population-Normalized Disaster Rates

These visualizations provide insights into historical climate patterns, geographic exposure, and disaster-related vulnerabilities.

## Conclusion

This project demonstrates how **Python-based data integration and Power BI visualization** can be used to explore relationships between climate change, natural disaster occurrence, and socioeconomic conditions.

The findings highlight the importance of considering both total disaster frequency and population-normalized measures when assessing geographic vulnerability.

While the observed trends provide useful insights, correlation alone does not establish causation, and changes in disaster reporting must also be considered.

## Future Improvements

Future work could incorporate machine learning forecasting, more detailed regional climate analysis, and additional socioeconomic indicators to improve disaster risk assessment.

## Project Team

**City University of Seattle**  
Master of Science in Data Science  
**DS522 – Data Acquisition and Analytics | Team 02**

- **Tung (Joseph) Tran**
- **Hindolo Dominic Magbity**

**Repository Maintainer:** [Tung Tran](https://github.com/josephtrn01)

---

*An academic data analytics project exploring global climate trends, natural disaster patterns, and socioeconomic vulnerability using Python and Power BI.*
