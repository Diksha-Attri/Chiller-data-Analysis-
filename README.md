# Industrial-Chiller-Performance-Analysis

This repository contains a complete analysis workflow for industrial chiller performance monitoring, and efficiency evaluation.  
The project demonstrates real-world data engineering, preprocessing, feature extraction, and exploratory analysis for industrial HVAC equipment.

## Project Overview

This project simulates an industrial chiller analytics pipeline, including:

- Data ingestion and structuring
- Cleaning and preprocessing
- Synthetic dataset generation (50,000 rows)
- Exploratory Data Analysis (EDA)
- Analysis of metrics such as:
  - Loading
  - Power consumption
  - Current
  - Suction/Discharge pressures
  - Evaporator/Condenser temperatures
  - Energy Efficiency Ratio (EER)
  - Specific Power Consumption (SPC)
- Time-series behaviour analysis

## Repository Structure

```
Industrial_chiller_Analysis/
│
├── data/
│   ├── synthetic_chiller_50k.csv      # High-realism synthetic dataset
│
├── notebooks/
│   └── Chiller_Analysis.ipynb         # Main analysis notebook
│
└── README.md
│
│
└── requirements.txt

```

## Synthetic Dataset Disclaimer

All data included in this repository is **fully synthetic**.  
Although it preserves the statistical behaviour, ranges, trends, and missing-value patterns of the sample provided,  
**no real operational or client data is present in this repository**.

The synthetic dataset is safe for:

- Public demonstrations  
- GitHub portfolio  
- Educational usage  
- Testing analytics pipelines  

## Sisai Technology Pvt. Ltd. – Disclaimer

This work was originally developed as part of chiller data analysis efforts for **Sisai Technology Pvt. Ltd.**  
However, **no confidential, proprietary, or operational data from Sisai Technology is included**.  
Only synthetic datasets generated from statistical patterns are used.

## Requirements

See the `requirements.txt` file for the list of dependencies.

## License

This project is intended for educational and portfolio use only.  
Any real-world deployment should be validated with actual equipment and domain experts.
