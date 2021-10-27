# map675-assignment-01.md
Authored by: Jessica Freeman, October 2021<br>
GitHub Page URL: https://jmfr236.github.io/map675-assignment-01-jmfr236/

## About
Groundwater is susceptible to contamination from activities on the land surface, and once contaminated can be hard to restore. Groundwater
sensitivity is determined by the ease of contaminants moving in the system. Levels range from 1 (low) to 5 (high), and is only accounting for naturally occurring hydrology patterns - not human based activities such as mining. This map is comparing groundwater sensitivity regions to locations of active mines in Kentucky. 
## Sources
- Ky Groundwater Sensitivity Regions: https://opengisdata.ky.gov/datasets/kygeonet::ky-groundwater-sensitivity-regions
- Ky Groundwater Sensitivity Report: https://kgs.uky.edu/kgsweb/download/rivers/sensitivity.ZIP
- Ky Rivers: https://opengisdata.ky.gov/datasets/kygeonet::ky-rivers
- Ky Permitted Mine Boundaries: https://opengisdata.ky.gov/datasets/kygeonet::ky-permitted-mine-boundaries
## Data Processing
- ogrinfo - layer details
- ogr2ogr - projection transformation, converting shapefiles to GeoJSON, extracting features (had some issues with this)
- Mapshaper - simplify detail


