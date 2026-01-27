# FEMA National Risk Index (NRI)
The goal of this assignment is to create a data visualization that answers the question:

How do FEMA National Risk Index scores for counties in California compare to those in other U.S. states?

The project focuses on data wrangling, visualization design, and clear communication of patterns in national risk data—without relying on maps.

## About FEMA’s National Risk Index (NRI)

The Federal Emergency Management Agency (FEMA) is a U.S. government agency whose mission is to help people before, during, and after disasters. In 2021, FEMA launched the National Risk Index (NRI), a dataset designed to help communities understand and compare their vulnerability to natural hazards.

The NRI provides information for communities at risk from 18 different natural hazards, offering a baseline risk measurement at the Census tract or county level. These measurements include:

- Expected Annual Loss (EAL)

- Social Vulnerability (SVI)

- Community Resilience (CRI)

Risk in the NRI is defined as the potential for negative impacts resulting from natural hazards and is calculated using the following equation:

Risk = Expected Annual Loss × Social Vulnerability ÷ Community Resilience

Risk = Expected Annual Loss × Social Vulnerability ÷ Community Resilience

Each hazard receives a hazard-specific risk score, and these are combined to create a composite risk score across all 18 hazards.

Scores are expressed as percentile rankings, meaning a county with a Risk Index percentile of 84.32 has a higher risk than 84.32% of all other U.S. counties. Counties are also assigned qualitative risk ratings ranging from Very Low to Very High.

In December 2025, FEMA integrated the National Risk Index into the Resilience Analysis and Planning Tool (RAPT), making NRI data more accessible for analysis and planning.

## Data Sources

FEMA National Risk Index (2025 Release)
Downloaded from FEMA’s Resilience Analysis and Planning Tool (RAPT) as a county-level CSV file.

Note:
The raw data file is stored locally in a data/ folder and is not tracked by GitHub. The data/ directory is included in .gitignore.
This repository contains coursework for HW #2 in EDS 240, which explores county-level natural hazard risk using FEMA’s National Risk Index (NRI).

## Repository Structure
```
eds240-nri-acs-viz/
    │
├── HW2.qmd              
├── README.md            
├── .gitignore           
│
├── data/                
    │
└── scripts/
```
