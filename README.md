# Bathymetry and Depth Zones Analysis
## Author: Bailey Jørgensen
### Contributors: Madison Enda, Michelle Yiv, Cori Lopazanski, Samantha Stevenson-Karl

This repository houses the analysis conducted by Bailey Jørgensen to analyze bathymetry and depth zone distribution in California MPAs, as part of the MarineBioMaps Capstone Project. 

This is a statewide and regional analysis, with summary statistics and mapping being conducted statewide, and also on a regional level. For the regional analysis, we utilized the 5 distinct regions defined by the California Department of Fish and Wildlife and the Marine Life Protection Act. They are definited as such:

**SCSR** = South Coast Study Region

**NCCSR** = North Central Coast Study Region

**CCSR** = Central Coast Study Region

**NCSR** = North Coast Study Region

**SFBSR** = San Francisco Bay Study Region

So far, the primary method of bathymetry and depth zone analysis is utilizing the depth zone categories integrated into the  [Pacific Marine and Estuarine Partnership (PMEP)](https://www.pacificfishhabitat.org/data/nearshore-cmecs-substrate-habitat/) data. These depth zones categories are a key component of both the biotic and substrate datasets, and within them the depthzones are defined as such:

- Value 0: Landward Zone
- Value 1: Core Zone (Estuary Overlap)
- Value 2: Core Zone (Shoreline to -30m), State Waters
- Value 3: Core Zone (Shoreline to -30m), Federal Waters
- Value 4: Seaward Zone (-30m to -100m), State Waters
- Value 5: Seaward Zone (-30m to -100m), Federal Waters
- Value 6: Deep Shelf or Channel (-100m to -200m), State Waters
- Value 7: Deep Shelf or Channel (-100m to -200m), Federal Waters
- Value 8: Outside PMEP Score (>-300m) or International Waters

The code found in this repository will regularly reference these PMEP depth zones.

## Data Used:

.rds files used throughout this repository were created in the rds_creation repository from this MarineBioMaps Github Organization. These files were used to load in the PMEP data filtered to California and California MPA study regions. See the rds_creation repository to view more details or recreate these .rds files. 

[California Department of Fish and Wildlife MPA Boundaries Shapefile](https://data.ca.gov/dataset/california-marine-protected-areas-ds582)

[Pacific Marine and Estuarine Partnership (PMEP) CMECS Nearshore Substrate Data](https://www.pacificfishhabitat.org/data/nearshore-cmecs-substrate-habitat/)

## File Contents

The Quarto Markdown files in this repository house the various analysis run to answer questions about MPA habitat components on a statewide, regional, or MPA specific level. The .qmd files are named for the respective areas being analyzed. 

## Repository Structure
```bash
├── statewide_depthzones_analysis.qmd
├── ccsr_depthzones_analysis.qmd
├── nccsr_depthzones_analysis.qmd
├── ncsr_depthzones_analysis.qmd
├── scsr_depthzones_analysis.qmd
├── sfbsr_depthzones_analysis.qmd
├── .gitignore
└── README.md
```


