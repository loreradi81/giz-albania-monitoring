# GIZ Albania Monitoring Dashboard

ETL pipeline and monitoring dashboard built for GIZ Albania (April 2025).

## Overview
End-to-end data pipeline that loads, cleans, and structures monitoring data 
from 8 source sheets, then visualises development impact across 4 megatrends 
in IBM Cognos Analytics.

## What this project does
- Loads and merges 8 data sheets: indicators, municipalities, donors, 
  beneficiaries, stakeholders, donor groups
- Normalises and explodes multi-value fields (city_ids, donor_ids, 
  stakeholder_ids) using Python/pandas
- Validates data integrity across all key dimensions
- Exports clean dataset (Excel + CSV) ready for BI tool ingestion
- Produces 4-panel IBM Cognos dashboard tracking development impact 2023–2025

## Key Insights from Dashboard
- **Economic Resilience** showed strongest growth 2023–2024
- **Livable Cities** declined continuously throughout 2023–2025
- **Top donors**: UN Agency and Bilateral Donors lead contributions
- **Top beneficiaries**: Social Groups (33.8%) and Governance & Administration (25.3%)
- **Geographic focus**: Highest project concentration in Tirana, Shkodër, Durrës

## Tools Used
- Python · pandas · Jupyter Notebooks
- IBM Cognos Analytics
- Excel / CSV output

## Files
| File | Description |
|------|-------------|
| `python_script_loren_radi.ipynb` | ETL pipeline — data loading, merging, cleaning, export |
| `GIZ Albania Monitoring Dashboard.pdf` | Final dashboard with insights |
| `README.md` | Project documentation |

## Author
Loren Radi · [lorenradi@gmail.com](mailto:lorenradi@gmail.com)
