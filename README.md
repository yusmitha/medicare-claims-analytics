# 🏥 Medicare Claims Analytics Project

## Overview
End-to-end data analysis project on **100,000+ real Medicare records** 
from CMS (Centers for Medicare & Medicaid Services) 2022 dataset.

## Key Findings
- 💰 Analyzed **$8.9 Billion** in Medicare payments
- 👥 Covered **30.7 Million** beneficiaries
- 🏥 Explored **102 provider types** across **58 states**
- 🥇 Hematology-Oncology leads in total Medicare payments
- 📍 California, Florida, and Texas are top states by payment volume

## Tech Stack
- **Python** (Pandas, NumPy, Matplotlib, Seaborn)
- **Jupyter Notebook** (VS Code)
- **Data Source:** CMS Medicare Physician & Other Practitioners 2022

## Project Structure
healthcare-claims-project/
│
├── data/              → Raw CMS Medicare dataset (not uploaded)
├── notebooks/         → Jupyter notebooks for analysis
│   └── 01_data_exploration.ipynb
├── output/            → Charts and cleaned data
│   ├── top_providers.png
│   ├── top_states.png
│   ├── avg_risk_score.png
│   ├── services_vs_payment.png
│   ├── gender_distribution.png
│   └── medicare_clean.csv
└── README.md
## Visualizations

### Top 10 Provider Types by Medicare Payment
![Top Providers](output/top_providers.png)

### Top 15 States by Medicare Payment
![Top States](output/top_states.png)

### Average Patient Risk Score by Provider Type
![Risk Score](output/avg_risk_score.png)

### Services vs Medicare Payment
![Scatter Plot](output/services_vs_payment.png)

### Gender Distribution of Beneficiaries
![Gender](output/gender_distribution.png)

## Author
**Yusmitha** | Data Analyst | MS Data Science - University of North Texas