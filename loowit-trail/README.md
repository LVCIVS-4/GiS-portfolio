# Loowit Trail GIS Analysis

**Author:** Lucius Williams IV
**Location:** Kent, WA  
**Started:** May 2026  

## Project Goal
Pre-trip spatial analysis of the Loowit Trail — a 30-mile 
circumnavigation of Mount St. Helens. Outputs include a 
printed field map, elevation profile, water source locations, 
lahar hazard overlay, and bail-out options.

## Projection
UTM Zone 10N, NAD83 (EPSG:26910) — to be confirmed on import

## Data Sources
| Dataset | Source | Format | Date Downloaded |
|---|---|---|---|
| Forest Administrative Boundaries | USFS | Shapefile | 2026-05 |
| National Forest System Trails | USFS | Shapefile | 2026-05 |
| NHD Washington State | USGS NHD | Geodatabase | 2026-05 |
| DEM 1/3 arc-second n47w122 | USGS National Map | GeoTIFF | 2026-05 |

## Status
- [x] Folder structure created  
- [x] Layers loaded into ArcGIS Pro  
- [x] CRS confirmed and project projection set  
- [x] Route extracted from USFS National Forest System Trails data (LOOWIT + JUNE LAKE segments) 
- [x] Add camp sites, water sources, no camp zone, and trail layers
- [x] Attribute table updated - Day_Segment field added
- [ ] Elevation profile extracted