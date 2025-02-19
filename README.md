# Queensland Traffic Data Analysis

## Overview
This project analyzes traffic data from Queensland, Australia, with the aim of reducing traffic accidents through data-driven insights. The analysis is based on comprehensive datasets provided by the Queensland Government Open Data Portal.

## Project Objectives
- Improve Queensland's traffic conditions and reduce the impact of peak periods
- Reduce traffic accidents through data-driven perspectives
- Raise residents' awareness of traffic safety

## Data Sources
All data is sourced from the Queensland Government Open Data Portal, covering a five-year period from 2018 to 2022.

### Datasets
1. Queensland Average Daily Traffic Volume Data
   - Size: 455,304 rows × 21 columns
   - Years covered: 2018-2022
   - Links for each year:
     - [2022 Data](https://shorturl.ac/2022)
     - [2021 Data](https://shorturl.ac/2021)
     - [2020 Data](https://shorturl.ac/2020)
     - [2019 Data](https://shorturl.ac/2019)
     - [2018 Data](https://shorturl.ac/2018)

2. Queensland Crash Data - Location & Characters
   - Size: 64,375 rows × 52 columns
   - Link: [Crash Location Data](https://shorturl.ac/crash_location)

3. Factors in Road Crashes
   - Size: 904 rows × 13 columns
   - Link: [Crash Factors Data](https://shorturl.ac/crash_factor)

4. Driver Demographics
   - Size: 3,445 rows × 16 columns
   - Link: [Driver Demographics Data](https://shorturl.ac/driver_demographics)

## Technical Details

### Technologies Used
- Programming Languages:
  - Python
  - SQL
- Key Libraries:
  - pandas
  - numpy

### Data Processing Methodology
1. Data Cleaning Steps:
   - Duplicate value removal
   - Missing data handling
   - Irrelevant data removal
   - Structural error correction
   - Outlier filtering
   - Data validation

2. Analysis Methods:
   - Time Series Analysis
   - User Profiling (Cluster Analysis)

## Key Findings and Recommendations
The analysis has yielded recommendations from two main perspectives:
1. Government Policy Perspective
2. Public Safety Awareness Perspective

## Project Structure
```text
project/
├── data/
│   ├── raw/          # Original datasets
│   └── processed/    # Cleaned and processed data
├── notebooks/        # Analysis notebooks
├── scripts/          # Python scripts for data processing
└── results/          # Analysis outputs and visualizations


## Data Access
Due to the large size of the datasets, the data files are not stored directly in this repository. Please use the links provided in the Data Sources section to download the original datasets.


---
*Note: This project is based on public data from the Queensland Government Open Data Portal and aims to contribute to traffic safety improvements in Queensland.*
