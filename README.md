# Bathymetry and Depth Zones Analysis

## Analysis conducted by Bailey Jørgensen to analyze bathymetry and depth zone distribution in California MPAs, as part of the MarineBioMaps Capstone Project. 

 Here is what the Pacific Marine and Estuarine Partnership (PMEP) defines depth zones, according to the metadata:

- Value 0: Landward Zone
- Value 1: Core Zone (Estuary Overlap)
- Value 2: Core Zone (Shoreline to -30m), State Waters
- Value 3: Core Zone (Shoreline to -30m), Federal Waters
- Value 4: Seaward Zone (-30m to -100m), State Waters
- Value 5: Seaward Zone (-30m to -100m), Federal Waters
- Value 6: Deep Shelf or Channel (-100m to -200m), State Waters
- Value 7: Deep Shelf or Channel (-100m to -200m), Federal Waters
- Value 8: Outside PMEP Score (>-300m) or International Waters

### Data:

.rds files created in the Biota and Substrate repositories from this organization were used to load in the PMEP data filtered to California. See those repositories to access these files. 

Shapefiles for CA MPA Boundaries were downloaded from the [California Department of Fish and Wildlife](https://data.ca.gov/dataset/california-marine-protected-areas-ds582).