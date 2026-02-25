# Climate Hazard Risk in Context: California Demographic Inequities and U.S. Statewide Comparisons

This repository contains workflows for two EDS 240 assignments completed as part of the MEDS program at the UCSB Bren School of Environmental Science & Management. Together, these assignments explore National Risk Index (NRI) scores in California relative to the rest of the United States and examine how climate hazard exposure varies across racial and ethnic groups within California. The work shown here applies skills learned throughout the course, selecting the most appropriate visualizations for the questions being asked.

This repository seeks to answer the following questions:

> *"How do FEMA National Risk Index scores for counties in California compare to those in other U.S. states?"*

> *"How does climate hazard risk exposure vary across ethnic groups in California?"*

This project focuses on data wrangling, visualization design, and communication of patterns in national risk data.

## About FEMA’s National Risk Index (NRI)

The Federal Emergency Management Agency (FEMA) is a U.S. government agency dedicated to help people before, during, and after disasters. In 2021, FEMA launched the National Risk Index (NRI), a dataset and online tool designed to help communities understand and compare their exposure to natural hazards. The NRI integrates scores for expected annual loss, social vulnerability, and community resilience to produce a composite risk score, which represents a county’s percentile ranking relative to other U.S. counties and ranges qualitatively from Very Low to Very High risk (FEMA, 2025). 

## About U.S. Census Bureau's Data 

The U.S. Census Bureau is the largest statistical agency of the federal government and serves as the nation’s primary provider of population and economic data. It maintains comprehensive demographic, social, and economic datasets for every U.S. state and territory. By collecting information at standardized geographic levels—such as states, counties, and census tracts—the Census Bureau enables consistent comparison and spatial analysis across regions. The analysis draws on county‑level race and ethnicity data for California obtained through the Census Data API. The API delivers programmatic access to American Community Survey (ACS) estimates.

## Repository Structure
```
eds240-nri-acs-viz
├── data
│   ├── ACS-1yr-2023-county-race-ethnicity.csv
│   └── National_Risk_Index_Counties.csv
├── eds240-nri-acs-viz.Rproj
├── HW2.pdf
├── HW2.qmd
├── HW3.pdf
├── HW3.qmd
├── LICENSE
├── README.html
├── README.md
└── repo-structure.png
```

## Data Sources & Access

FEMA National Risk Index (2025 Release)
Downloaded from ![FEMA’s Resilience Analysis and Planning Tool (RAPT)](https://experience.arcgis.com/experience/0a317e8998534c30a9b2d3861c814d42/?views=Add-Data) as a county-level CSV file.

U.S. Census Bureau. (2023). American Community Survey 1-Year Estimates, Tables B01003, B02001, and B03002 [Data set]. https://www.census.gov/programs-surveys/acs
*Census data were retrieved programmatically using the {tidycensus} R package, which interfaces with the U.S. Census Bureau’s Census Data API.*

Note:

The raw data file is stored locally in the `data/` directory and is not tracked by GitHub, which is included in the `.gitignore` file.

This repository contains coursework for Homework #2 and Homework #3 from EDS 240, which explores county-level natural hazard risk and demographic information using FEMA’s National Risk Index (NRI) variables  and U.S. Census Bureau ethnic group variables. 

## Authors & Contributors

**Melannie Moreno Rolón**

Master of Environmental Data Science (MEDS), UCSB Bren School
GitHub: https://github.com/mmorenorolon

## References & Acknowledgements

Data Visualization & Communication. (2025). Github.Io. Retrieved January 28, 2026, from https://eds-240-data-viz.github.io/

FEMA. Resilience Analysis and Planning Tool (RAPT). Retrieved January 28, 2026,
https://www.fema.gov/rapt

National Risk Index Data. (2025). Fema.Gov. Retrieved January 28, 2026, from https://www.fema.gov/sites/default/files/documents/fema_national-risk-index_technical-documentation.pdf?utm_source=chatgpt.com

U.S. Census Bureau. (2023). American Community Survey 1-Year Estimates, Tables B01003, B02001, and B03002 [Data set]. https://www.census.gov/programs-surveys/acs



