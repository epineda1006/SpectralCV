# SpectralCV — Satellite-Based Orchard Stress Mapping
F3i Innovate Data Challenge #2 | Team: SpectralCV | May 2026

## Overview
SpectralCV detects persistent stress zones in Central Valley orchards 
using 6 years of Sentinel-2 satellite imagery (2019-2024) across 6 sites.

## How to Run
1. Open SpectralCV_pipeline.ipynb in NDP JupyterHub
2. Run Section 0 (Install + Imports + Config)
3. Run sections in order: 1 → 2 → 3 → 6 → 8
4. Outputs save automatically to outputs/stress_maps/ and outputs/time_series/

## Requirements
See requirements.txt. Install with: pip install -r requirements.txt

## Sites
Fresno, Kings, Kern, Stanislaus, Tulare, Partner (HMC Farms)

## Key Results
- Fresno: 9.8% high stress, 20.3% mild, 69.8% healthy
- Kings: 7.0% high stress, 24.1% mild, 68.9% healthy  
- Partner (HMC Farms): 8.9% high stress, 27.6% mild, 63.6% healthy
- All sites show 2022 drought signal (40%+ NDVI decline from 2019 baseline)

## Platform
National Data Platform (NDP) JupyterHub
