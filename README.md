# SpectralCV — Satellite-Based Orchard Stress Mapping
F3i Innovate Data Challenge #2 | Team: SpectralCV | May 2026
Contributors: Eric Pineda Ramirez, Ronnie Pabelonio

## Overview
SpectralCV detects persistent stress zones in Central Valley orchards
using 6 years of Sentinel-2 satellite imagery (2019-2024) across 6 sites.

## Repository Structure

### Main Pipeline (Eric)
- `SpectralCV_pipeline.ipynb` — Full end-to-end pipeline covering Fresno,
  Kings, and Partner (HMC Farms) sites. Start here.

### Site-Specific Notebooks (Ronnie)
Located in the `notebooks/` folder:
- `notebooks/SpectralCV_Kern.ipynb` — Kern County site analysis
- `notebooks/SpectralCV_Stanislaus.ipynb` — Stanislaus County site analysis
- `notebooks/SpectralCV_Tulare.ipynb` — Tulare County site analysis

## How to Run

### Main Pipeline
1. Open NDP JupyterHub at nationaldataplatform.org
2. Navigate to your persistent storage folder
3. Open `SpectralCV_pipeline.ipynb`
4. Run Section 0 (Install + Imports + Config)
5. Run sections in order: 1 → 2 → 3 → 6 → 8
6. Outputs save automatically to `outputs/stress_maps/` and `outputs/time_series/`

### Site-Specific Notebooks
1. Open NDP JupyterHub
2. Navigate to the `notebooks/` folder
3. Open the notebook for the site you want to analyze
4. Run all cells top to bottom

## Sites Covered
| Site | Notebook | High Stress | Mild Stress | Healthy |
|------|----------|-------------|-------------|---------|
| Fresno | SpectralCV_pipeline.ipynb | 11.7% | 30.2% | 58.0% |
| Kings | SpectralCV_pipeline.ipynb | 1.8% | 22.8% | 75.5% |
| Partner (HMC Farms) | SpectralCV_pipeline.ipynb | 10.3% | 26.4% | 63.4% |
| Kern | notebooks/SpectralCV_Kern.ipynb | TBD | TBD | TBD |
| Stanislaus | notebooks/SpectralCV_Stanislaus.ipynb | 11.1% | 13.3% | 75.7% |
| Tulare | notebooks/SpectralCV_Tulare.ipynb | 14.5% | 18.6% | 66.9% |

## Requirements
Install dependencies with:
## Key Findings
- All 6 sites show 2022 drought signal (35-42% NDVI decline from 2019 baseline)
- Stress zones cluster spatially and persist across multiple seasons
- Pipeline generalizes across different crop types and geographies

## Platform
National Data Platform (NDP) JupyterHub
