# Datasets

A curated collection of datasets for GeoAI, Earth observation, remote sensing, GIS, and environmental applications.

The goal of this repository is to make useful geospatial datasets easier to discover and compare across different research and application areas.

## Categories

- [Satellite and Aerial Imagery](#satellite-and-aerial-imagery)
- [LiDAR and 3D Geospatial Data](#lidar-and-3d-geospatial-data)
- [Land Cover and Land Use](#land-cover-and-land-use)
- [Agriculture](#agriculture)
- [Forests and Vegetation](#forests-and-vegetation)
- [Biomass and Carbon](#biomass-and-carbon)
- [Protected Lands and Parks](#protected-lands-and-parks)
- [Socioeconomic and Demographic Data](#socioeconomic-and-demographic-data)
- [Benchmarks](#benchmarks)

---

## Satellite and Aerial Imagery

Satellite, aerial, multispectral, and other remotely sensed imagery resources.

| Resource | Description | Coverage | Resolution | Access |
|---|---|---|---|---|
| [Microsoft Planetary Computer](https://planetarycomputer.microsoft.com/) | Cloud-based platform providing access to large Earth observation and environmental datasets through STAC and related APIs. | Global | Varies by dataset | Open |
| [Microsoft Planetary Computer STAC API](https://planetarycomputer.microsoft.com/api/stac/v1) | STAC API for programmatic discovery and access to datasets hosted by Microsoft Planetary Computer. | Global | Varies by dataset | Open |
| [Microsoft Planetary Computer Data Catalog](https://planetarycomputer.microsoft.com/catalog) | Catalog for browsing Earth observation and environmental datasets available through Microsoft Planetary Computer. | Global | Varies by dataset | Open |
| [Microsoft Planetary Computer Explorer](https://planetarycomputer.microsoft.com/explore) | Interactive interface for exploring spatial datasets available through Microsoft Planetary Computer. | Global | Varies by dataset | Open |
| [NAIP Imagery](https://nrcs.app.box.com/v/naip/folder/17936490251) | USDA National Agriculture Imagery Program aerial imagery for the United States. | United States | Varies by year and location; commonly sub-meter to 1 m | Open |
| [WorldView-3](https://earth.esa.int/eogateway/missions/worldview-3#data-section) | Very-high-resolution commercial satellite imagery with panchromatic and multispectral capabilities. | Global | Up to approximately 0.31 m panchromatic | Commercial / limited research access |
| [NASA Earthdata Search – WorldView-3](https://search.earthdata.nasa.gov/search?as%5Bplatforms%5D%5B0%5D=Space-based%20Platforms%3AEarth%20Observation%20Satellites%3AWorldview%3AWORLDVIEW-3&fpb0=Space-based%20Platforms&fpc0=Earth%20Observation%20Satellites&fpsc0=Worldview&fps0=WORLDVIEW-3) | NASA Earthdata interface for discovering available WorldView-3-related datasets and collections. | Global | Varies by product | Depends on dataset |
| [Google Satellite Embedding](https://developers.google.com/earth-engine/datasets/catalog/GOOGLE_SATELLITE_EMBEDDING_V1_ANNUAL) | Annual geospatial embedding dataset derived from Earth observation imagery for downstream mapping and analysis tasks. | Global | Varies by product | Available through Google Earth Engine |

---

## LiDAR and 3D Geospatial Data

Airborne LiDAR, spaceborne LiDAR, point clouds, elevation, canopy structure, and other 3D geospatial datasets.

| Resource | Description | Coverage | Data Type | Access |
|---|---|---|---|---|
| [USGS 3DEP LiDAR](https://data.usgs.gov/datacatalog/data/USGS:b7e353d2-325f-4fc6-8d95-01254705638a) | U.S. Geological Survey 3D Elevation Program LiDAR point-cloud collection. | United States | Airborne LiDAR / point clouds | Open |
| [USGS 3DEP LiDAR Basic Example](https://usgs-lidar.gishub.org/) | Interactive example and workflow for accessing and working with USGS 3DEP LiDAR data. | United States | LiDAR / elevation | Open |
| [OpenTopography](https://opentopography.org/) | Platform providing access to high-resolution topography, LiDAR, and related geospatial datasets. | Global | LiDAR / DEM / point clouds | Open / varies by dataset |
| [NOAA Miami-Dade 2021 LiDAR](https://portal.opentopography.org/noaaDataset?noaaID=10338) | NOAA LiDAR dataset covering Miami-Dade County, Florida. | Miami-Dade County, Florida | Airborne LiDAR | Open |
| [Florida LiDAR Resources](https://www.floridagio.gov/pages/lidar-resources) | Florida Geographic Information Office resources for locating LiDAR and elevation datasets. | Florida, United States | LiDAR / elevation | Open |
| [GEDI](https://www.earthdata.nasa.gov/data/instruments/gedi-lidar) | NASA Global Ecosystem Dynamics Investigation spaceborne LiDAR measurements of forest structure and surface elevation. | Near-global land coverage within GEDI orbital range | Spaceborne waveform LiDAR | Open |
| [NASA GEDI Sensor Information](https://www.earthdata.nasa.gov/sensors/gedi) | NASA Earthdata information and access resources for GEDI observations. | Near-global land coverage within GEDI orbital range | Spaceborne LiDAR | Open |
| [NEON LiDAR](https://www.neonscience.org/data-collection/lidar) | Airborne LiDAR collected by the National Ecological Observatory Network. | United States NEON sites | Airborne LiDAR | Open |
| [NEON Data Portal](https://www.neonscience.org/data) | NEON ecological and remote sensing datasets, including airborne observations. | United States NEON sites | Multiple | Open |
| [NEON Canopy Height Model](https://developers.google.com/earth-engine/datasets/catalog/projects_neon-prod-earthengine_assets_CHM_001) | NEON canopy height model collection available through Google Earth Engine. | United States NEON sites | Canopy height model | Open |
| [High Resolution 1 m Global Canopy Height Maps](https://gee-community-catalog.org/projects/meta_trees/) | High-resolution canopy height products available through the Google Earth Engine Community Catalog. | Global | Canopy height | Open |
| [Global Canopy Height](https://langnico.github.io/globalcanopyheight/) | High-resolution global canopy height model derived from remote sensing observations. | Global | Canopy height | Open |

---

## Land Cover and Land Use

National and global land-cover, land-use, surface characterization, and land-change datasets.

| Resource | Description | Coverage | Resolution | Access |
|---|---|---|---|---|
| [Dynamic World](https://dynamicworld.app/) | Near-real-time global land-cover dataset derived from Sentinel-2 imagery using machine learning. | Global | 10 m | Open |
| [National Land Cover Database](https://www.usgs.gov/centers/eros/science/national-land-cover-database) | U.S. land-cover and land-cover change products maintained by USGS. | United States | Typically 30 m | Open |
| [MRLC Annual NLCD Data](https://www.mrlc.gov/data?f%5B0%5D=category%3ALand%20Cover&f%5B1%5D=project_tax_term_term_parents_tax_term_name%3AAnnual%20NLCD) | Download portal for Annual NLCD land-cover products. | United States | Varies by product | Open |
| [NLCD Class Legend](https://www.mrlc.gov/data/legends/national-land-cover-database-class-legend-and-description) | Official land-cover class definitions and descriptions for NLCD. | United States | Not applicable | Open |
| [NLCD ScienceBase Collection](https://www.sciencebase.gov/catalog/item/6345b637d34e342aee0863aa) | USGS ScienceBase record providing access to NLCD-related products. | United States | Varies by product | Open |
| [Florida Statewide Land Use and Land Cover](https://geodata.dep.state.fl.us/datasets/FDEP::statewide-land-use-land-cover/about) | Florida Department of Environmental Protection statewide land-use and land-cover dataset. | Florida, United States | Varies | Open |
| [Land-Use Harmonization](https://luh.umd.edu/data.shtml) | Global historical and future land-use datasets used in Earth system and climate modeling. | Global | Varies by product | Open |
| [FGDL Map Viewer](https://fgdl.org/fgdlmap/) | Florida Geographic Data Library map viewer providing access to numerous statewide geospatial layers. | Florida, United States | Varies | Open |
| [GEE Community Catalog – Data Themes](https://gee-community-catalog.org/projects/) | Community-maintained catalog of geospatial datasets available through or compatible with Google Earth Engine. | Global | Varies | Open |

---

## Agriculture

Datasets related to crops, agricultural land, field boundaries, farmland, crop monitoring, and agricultural remote sensing.

| Resource | Description | Coverage | Resolution | Access |
|---|---|---|---|---|
| [USDA NASS Cropland Data Layer](https://developers.google.com/earth-engine/datasets/catalog/USDA_NASS_CDL) | Annual crop-specific land-cover dataset produced by USDA National Agricultural Statistics Service. | United States | Varies by year; commonly 30 m | Open |
| [AgriBound](https://montimaj.github.io/agribound/) | Agricultural field-boundary resource for remote sensing and GeoAI applications. | Varies by dataset | Field boundaries | Open / research |
| [Florida Statewide Land Use and Land Cover](https://geodata.dep.state.fl.us/datasets/FDEP::statewide-land-use-land-cover/about) | Statewide land-use dataset containing agricultural and related land-use classes. | Florida, United States | Varies | Open |
| [USDA NAIP Imagery](https://nrcs.app.box.com/v/naip/folder/17936490251) | High-resolution aerial imagery widely used for crop, field, farm, and agricultural mapping. | United States | Sub-meter to 1 m depending on year and location | Open |

---

## Forests and Vegetation

Datasets related to tree crowns, canopy structure, forest cover, vegetation, and tree species.

| Resource | Description | Coverage | Data Type / Resolution | Access |
|---|---|---|---|---|
| [3D Trees](https://3dtrees.earth/) | High-resolution tree and forest structure resource supporting tree-scale Earth observation research. | Varies | Tree / canopy structure | Open / research |
| [DeadTrees.Earth](https://deadtrees.earth/) | Geospatial resource focused on tree mortality and dead-tree mapping. | Varies | Tree-level / remote sensing | Open / research |
| [SelvaBox](https://proceedings.iclr.cc/paper_files/paper/2026/hash/1c3e0cb1dd13ab2497a8ebd5129ad166-Abstract-Conference.html) | High-resolution dataset for tropical tree crown detection. | Tropical regions represented in dataset | High-resolution imagery / tree crowns | Research |
| [TreeSatAI Benchmark Archive](https://essd.copernicus.org/articles/15/681/2023/) | Multi-sensor, multi-label benchmark dataset for tree species classification using remote sensing. | Europe / study regions represented in dataset | Multi-sensor | Open / research |
| [StreetTree](https://arxiv.org/abs/2602.19123) | Large-scale global benchmark for fine-grained tree species classification. | Global | Street-level / tree species imagery | Research |
| [NEON Canopy Height Model](https://developers.google.com/earth-engine/datasets/catalog/projects_neon-prod-earthengine_assets_CHM_001) | Canopy height models derived from NEON airborne LiDAR. | United States NEON sites | Canopy height | Open |
| [High Resolution 1 m Global Canopy Height Maps](https://gee-community-catalog.org/projects/meta_trees/) | High-resolution canopy height products for tree and vegetation analysis. | Global | Approximately 1 m | Open |
| [Global Canopy Height](https://langnico.github.io/globalcanopyheight/) | Global high-resolution canopy height dataset. | Global | High resolution | Open |

---

## Biomass and Carbon

Datasets related to aboveground biomass, forest carbon, vegetation carbon, and ecosystem carbon estimation.

| Resource | Description | Coverage | Data Type | Access |
|---|---|---|---|---|
| [FIA BIGMAP Tree Species Aboveground Biomass Layers](https://data.fs.usda.gov/geodata/rastergateway/bigmap/index.php) | USDA Forest Service raster products estimating tree-species-level aboveground biomass. | United States | Raster biomass layers | Open |
| [CTrees Aboveground Biomass Data](https://ctrees.org/news/2026-aboveground-biomass-data-release) | Aboveground biomass data products developed for forest carbon and ecosystem monitoring. | Large-area / global products | Aboveground biomass | Check dataset terms |
| [BioMassters](https://nascetti-a.github.io/BioMasster/) | Benchmark dataset for forest biomass estimation using multimodal satellite time series. | Study regions represented in dataset | Sentinel-1 / Sentinel-2 time series and biomass | Open / research |
| [Planet Forest Carbon](https://www.planet.com/products/forest-carbon/) | Forest carbon products derived from satellite and other Earth observation data. | Global / product-dependent | Forest carbon / biomass | Commercial |
| [GEDI](https://www.earthdata.nasa.gov/data/instruments/gedi-lidar) | Spaceborne LiDAR observations widely used for forest structure and biomass estimation. | Near-global land coverage within GEDI orbital range | LiDAR-derived structure and biomass products | Open |
| [FIA BIGMAP](https://data.fs.usda.gov/geodata/rastergateway/bigmap/index.php) | Forest Service spatial modeling products connecting Forest Inventory and Analysis observations with remote sensing. | United States | Raster | Open |

---

## Protected Lands and Parks

Datasets related to protected areas, national parks, state parks, conservation lands, recreation, and visitation.

| Resource | Description | Coverage | Data Type | Access |
|---|---|---|---|---|
| [PAD-US](https://www.usgs.gov/programs/gap-analysis-project/science/pad-us-data-download) | Protected Areas Database of the United States containing public lands and conservation areas. | United States | Vector boundaries / attributes | Open |
| [National Park Service Visitor Use Statistics](https://irma.nps.gov/Stats/) | Official visitation statistics for units of the U.S. National Park System. | United States | Tabular visitation data | Open |
| [ParkServe Data](https://www.tpl.org/park-data-downloads) | Park and park-access datasets from Trust for Public Land. | United States | Parks / accessibility / urban park data | Open / terms vary |
| [Florida State Parks Boundaries](https://hub.arcgis.com/datasets/bd190cf3d3934fbd9529dfe1c8c8772c_0/explore) | Geospatial boundaries for Florida State Parks. | Florida, United States | Vector boundaries | Open |
| [Florida Forever](https://www.fnai.org/conslands/florida-forever) | Conservation lands and acquisition information associated with Florida Forever. | Florida, United States | Conservation lands | Open |
| [Florida Wildlife Corridor Maps](https://floridawildlifecorridor.org/maps/) | Mapping resources for the Florida Wildlife Corridor and connected conservation lands. | Florida, United States | Maps / conservation areas | Open |
| [NPS Vector Boundaries](https://roblabs.com/nps-vector-boundaries/) | Vector boundary resources for National Park Service units. | United States | Vector boundaries | Open |
| [Florida State Park Attendance Report](https://www.floridastateparks.org/sites/default/files/media/file/AttendanceReport_AllData.pdf) | Historical attendance statistics for Florida State Parks. | Florida, United States | Visitation statistics | Open |
| [U.S. National Park Visit Data](https://www.responsible-datasets-in-context.com/posts/np-data/) | Curated historical U.S. National Park visitation dataset and contextual documentation. | United States | Visitation statistics | Open |

---

## Socioeconomic and Demographic Data

Population, demographic, parcel, socioeconomic, and other human-environment geospatial datasets.

| Resource | Description | Coverage | Data Type | Access |
|---|---|---|---|---|
| [U.S. Census Urban Areas](https://www.census.gov/cgi-bin/geo/shapefiles/index.php?year=2023&layergroup=Urban+Areas) | Census-defined Urban Area boundaries available as TIGER/Line shapefiles. | United States | Vector boundaries | Open |
| [Census Geographic Identifiers](https://www.census.gov/programs-surveys/geography/guidance/geo-identifiers.html) | Documentation for GEOIDs used to connect Census geographic units with demographic and socioeconomic data. | United States | Geographic identifiers | Open |
| [Florida Statewide Parcels](https://www.arcgis.com/home/item.html?id=efa909d6b1c841d298b0a649e7f71cf2) | Statewide parcel dataset for Florida. | Florida, United States | Parcel polygons / attributes | Check source terms |
| [National Park Service Visitor Use Statistics](https://irma.nps.gov/Stats/) | Visitor-use statistics that can support human-environment and recreation analyses. | United States | Tabular visitation data | Open |
| [Florida State Park Attendance Report](https://www.floridastateparks.org/sites/default/files/media/file/AttendanceReport_AllData.pdf) | Historical state park attendance information useful for recreation and ecosystem-service studies. | Florida, United States | Tabular visitation data | Open |

---

## Benchmarks

Benchmark datasets for GeoAI, remote sensing, object detection, semantic segmentation, classification, multimodal learning, and related tasks.

| Resource | Task | Data Type | Coverage / Domain | Access |
|---|---|---|---|---|
| [DOTA](https://captain-whu.github.io/DOTA/dataset.html) | Oriented object detection | High-resolution aerial imagery | Multiple geographic regions | Open / research |
| [iSAID](https://captain-whu.github.io/iSAID/) | Instance segmentation | High-resolution aerial imagery | Derived from DOTA imagery | Open / research |
| [GEO-Bench-2](https://github.com/The-AI-Alliance/GEO-Bench-2) | GeoAI foundation model benchmarking | Multiple Earth observation datasets | Multiple tasks and regions | Open |
| [TreeSatAI Benchmark Archive](https://essd.copernicus.org/articles/15/681/2023/) | Multi-label tree species classification | Multi-sensor remote sensing | Forest / vegetation | Open |
| [StreetTree](https://arxiv.org/abs/2602.19123) | Fine-grained tree species classification | Street-level imagery | Global | Research |
| [SelvaBox](https://proceedings.iclr.cc/paper_files/paper/2026/hash/1c3e0cb1dd13ab2497a8ebd5129ad166-Abstract-Conference.html) | Tree crown detection | High-resolution imagery | Tropical forests | Research |
| [BioMassters](https://nascetti-a.github.io/BioMasster/) | Forest biomass estimation | Multimodal satellite time series | Forest ecosystems | Open / research |
