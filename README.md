# Global Internet Adoption Analysis (1990–2025)

## Project Overview

This project analyzes internet adoption trends across ten selected countries between 1990 and 2025 using the World Bank World Development Indicators (WDI) dataset.

The objective is to compare internet adoption levels, identify long-term trends, and present findings through an interactive Power BI dashboard.

---

## Dataset

**Source:** World Bank World Development Indicators (WDI)

https://datatopics.worldbank.org/world-development-indicators/

**Dataset Used:**
- WDICSV.csv

---

## Tools Used

- Python
- Pandas
- Jupyter Notebook / VS Code
- Microsoft Power BI
- GitHub

---

## Data Cleaning Process

The following steps were performed:

- Loaded the dataset using Pandas
- Explored dataset structure
- Filtered internet-related indicators
- Selected the indicator:
  - Individuals using the Internet (% of population)
- Selected ten representative countries
- Removed regional and income-group aggregates
- Converted the dataset from wide format to long format using melt()
- Converted Year into integer format
- Ensured Value remained numeric
- Removed missing values
- Exported the cleaned dataset for Power BI

---

## Dashboard Features

The Power BI dashboard includes:

- KPI Cards
- Area Chart
- Line Chart
- Pie Chart
- Clustered Bar Chart
- Country Slicer
- Year Slicer

---

## Key Findings

- Canada recorded the highest average internet adoption.
- Nigeria recorded the lowest average internet adoption.
- Internet adoption increased significantly after the mid-2010s.
- Developed countries consistently maintained higher adoption rates than developing countries.

---

## Recommendations

- Continue investing in digital infrastructure.
- Improve affordable internet access.
- Expand digital literacy programmes.
- Strengthen public-private partnerships to reduce the digital divide.

---

## Project Structure

```
Week 8 AnalystLab/
│
├── Cleaned_Internet_Indicators.csv
├── Internet_Adoption_Analysis.ipynb
├── Internet_Adoption_Dashboard.pbix
├── Dashboard Screenshot.png
├── Final Report.pdf
└── README.md
```

---

## Author

**Odeh Olakunle Joshua**

Data Analytics Intern | AnalystLab Africa (Batch B)

GitHub: https://github.com/TheOlaAji

LinkedIn: https://www.linkedin.com/in/olakunle-odeh-51660a1b2
