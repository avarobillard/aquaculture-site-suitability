# Aquaculture Site Suitability Analysis

Author: Ava Robillard

This repository contains an analysis of which Exclusive Economic Zones (EEZ) on the West Coast of the US are best suited to developing marine aquaculture for several species.

The projects aims specifically to produce maps of Exclusive Economic Zones (EEZ) with the most suitable area for a specified marine species based upon their optimal sea surface temperature and depth.

## Repository Structure

The **aquaculture_site_analysis.qmd** file contains the main analysis and visualizations.

The **data** folder contains the Sea Surface Temperature (SST), Bathymetry (depth), and EEZ boundary data imported for the analysis.

```
aquaculture-site-suitability
├── README.md
├── aquaculture-site-suitability.Rproj
├── aquaculture_site_analysis.qmd
|   .gitignore
    └── data
        ├── average_annual_sst_2008.tif
        ├── average_annual_sst_2009.tif
        ├── average_annual_sst_2010.tif
        ├── average_annual_sst_2011.tif
        ├── average_annual_sst_2012.tif
        ├── depth.tif
        ├── wc_regions_clean.dbf
        ├── wc_regions_clean.prj
        ├── wc_regions_clean.shp
        └── wc_regions_clean.shx
```

## Data

The Sea Surface Temperature (SST) data was generated from [NOAA's 5km Daily Global Satellite Sea Surface Temperature Anomaly v3.1](https://coralreefwatch.noaa.gov/product/5km/index_5km_ssta.php). An annual average from the years 2008 to 2012 were used for site suitability in this analysis.

The depth data was sourced from the [General Bathymetric Chart of the Oceans (GEBCO),](https://www.gebco.net/data-products/gridded-bathymetry-data#area) which provides elevation data in GeoTiff formats.

The maritime boundaires in this analysis were designated using Exclusive Economic Zones off the west coast of the US from [Marineregions.org](https://www.marineregions.org/eez.php), which provides a layer of EEZ-polygons.

## References

This assignment was created as a part of EDS 223: Geospatial Analysis & Remote Sensing, taught by Annie Adams.

**Data**

[NOAA's 5km Daily Global Satellite Sea Surface Temperature Anomaly v3.1](https://coralreefwatch.noaa.gov/product/5km/index_5km_ssta.php). Accessed Nov 16, 2025

[General Bathymetric Chart of the Oceans (GEBCO)](https://www.gebco.net/data-products/gridded-bathymetry-data#area). Accessed Nov 16, 2025

[Marineregions.org](https://www.marineregions.org/eez.php). Accessed Nov 16, 2025
