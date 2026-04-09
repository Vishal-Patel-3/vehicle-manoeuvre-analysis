# vehicle-manoeuvre-analysis

**Dataset**

The data is sourced from the UK Department for Transport road safety dataset:
https://data.dft.gov.uk/road-accidents-safety-data/dft-road-casualty-statistics-vehicle-provisional-2025.csv

The dataset contains coded variables (e.g. manoeuvre type, age band, sex). The meanings of these codes were obtained from the official data guide:
https://assets.publishing.service.gov.uk/media/691c6440e39a085bda43eed6/dft-road-casualty-statistics-road-safety-open-dataset-data-guide-2024.xlsx

These coded variables were recoded into descriptive categories and, where appropriate, grouped into broader classifications to improve interpretability.

**Overview**

This project analyses UK road casualty vehicle data to explore how vehicle manoeuvres vary by driver characteristics, specifically sex and age group. The aim is to identify patterns in driving behaviour and understand how different groups are represented across manoeuvre types.

**Methods**

- Data cleaning and filtering (removal of missing values and unrealistic age groups)
- Recoding of categorical variables using official documentation
- Grouping of manoeuvres into broader categories
- Calculation of frequency distributions and percentages
- Visualisation using bar charts

**Key Findings**

- Most incidents occur during routine forward movement (“Going ahead”)
- Male drivers are more frequently represented across all manoeuvre types
- The largest differences by sex appear in overtaking manoeuvres
- Incidents are concentrated among typical driving-age groups

**Files**
- Collision_analysis.ipynb — Full analysis notebook (code, data processing, and visualisations)
- Collision_analysis.html — Clean report version of the analysis (no code, suitable for viewing)
