# DLR - German Aerospace Center

The German Aerospace Center (DLR) Earth Observation Center (EOC) provides public APIs for accessing Earth observation satellite data, remote sensing products, and scientific datasets from German aerospace research missions.

## APIs

The EOC Geoservice provides OGC-compliant discovery, visualization, and direct download services for geospatial data hosted by the German Satellite Data Archive (D-SDA). Services include:

- **STAC API** - SpatioTemporal Asset Catalog with 80+ Earth observation collections
- **WMS (Imagery)** - Web Map Service for satellite imagery visualization
- **WCS (Imagery)** - Web Coverage Service for data extraction and download
- **WMS (Basemap)** - Basemap and reference data visualization including SRTM DEM
- **WCS (Basemap)** - Coverage download for basemap datasets
- **WMS (Land)** - Land cover and land use layers (WSF, crop types, forest)
- **WMS (Atmosphere)** - Atmospheric products (Sentinel-5P TROPOMI trace gases)
- **EOWEB GeoPortal** - Multi-mission data portal for browsing and ordering EO data

## Data Coverage

- TanDEM-X global digital elevation models (90m resolution)
- Sentinel-2 multispectral imagery with atmospheric corrections
- Sentinel-5P TROPOMI atmospheric trace gas products
- EnMAP hyperspectral satellite imagery
- DESIS hyperspectral data from the ISS
- World Settlement Footprint global urban mapping
- MODIS-based Global Water Pack (daily/monthly/yearly)
- Forest structure and canopy data for Germany
- CORINE land cover data for Europe

## Access

All EOC Geoservice APIs are free and publicly accessible without registration. The EOWEB GeoPortal offers guest browsing and free registered user access for dataset ordering. Scientific access to TanDEM-X and TerraSAR-X data is available through a proposal-based process.

## Links

- Portal: https://geoservice.dlr.de/web/
- STAC API: https://geoservice.dlr.de/eoc/ogc/stac/v1/
- EOWEB GeoPortal: https://eoweb.dlr.de/egp/
- Data Assets Catalog: https://geoservice.dlr.de/data-assets/
- Data Access Information: https://www.dlr.de/en/eoc/research-transfer/topics/satellite-data/data-access
- GitHub: https://github.com/dlr-eoc
- Contact: geoservice@dlr.de
