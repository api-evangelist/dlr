# DLR - German Aerospace Center

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
