# Modeling Amphibian Habitat Persistence via Fungal Network Proxies

This project investigates whether belowground fungal networks—specifically mycorrhizal fungi—serve as a hidden driver of amphibian breeding habitat persistence in forest–wetland mosaics of the Chesapeake Bay watershed. The study aims to develop a spatial model that uses environmental proxies to estimate fungal network strength and overlay this with amphibian occurrence data to identify high-value conservation areas and potential climate refugia.

## Background

Mycorrhizal fungi play a critical but understudied role in forest ecosystem resilience, soil structure, and nutrient exchange. Recent ecological literature suggests a potential connection between fungal network density and aboveground biodiversity—including amphibians, which are sensitive indicators of habitat integrity and microclimatic change.

This project builds on that emerging connection by asking:

**Can we model amphibian breeding persistence using GIS-based proxies for belowground fungal networks?**

## Objectives

- Identify and spatially map environmental variables that serve as reliable proxies for fungal network strength (e.g., soil moisture, organic matter, canopy structure, pH)
- Overlay proxy layers with amphibian breeding occurrence records (e.g., *Rana sylvatica*, *Ambystoma opacum*)
- Develop a logistic regression or AI-based spatial model to predict breeding habitat persistence
- Validate outputs with known breeding hotspots or long-term monitoring sites
- Highlight potential climate-resilient refugia for amphibian conservation across the Chesapeake Bay watershed


## Methods (Planned)

### GIS & Spatial Analysis
- Software: QGIS, GRASS GIS, ArcGIS Pro (limited)
- Hydrological correction and flow modeling (QGIS GRASS tools)
- Soil and vegetation raster processing
- Creation of spatial indices for fungal network proxies

### Modeling & Statistics
- Logistic regression and/or machine learning classification
- Variable preprocessing: normalization, collinearity assessment, PCA
- Cross-validation and spatial holdout tests
- ROC/AUC, sensitivity-specificity evaluation
- Visualization in R with `ggplot2`, `leaflet`, or `tmap`

### UAV Integration (Planned)
- FAA Part 107 remote pilot certification in progress
- Planned canopy and microtopographic mapping with UAV
- Integration of drone-based NDVI or structural imagery into final model

## Study Area

The study focuses on forest–wetland mosaics in the Chesapeake Bay region of Maryland, with an emphasis on known breeding areas for woodland and vernal pool–dependent amphibians. Target taxa may include *Rana sylvatica*, *Ambystoma opacum*, and *Hyla versicolor*.

## References

Key literature and datasets will be listed here.

- Frey et al. (2020). Soil Mycorrhizal Networks and Forest Resilience. *Ecological Applications*
- U.S. EPA (2023). Chesapeake Bay Watershed Data Portal
- U.S. Geological Survey (USGS) Amphibian Research and Monitoring Initiative (ARMI)

## Project Status

**In Development** — Spatial design and data acquisition in progress.  
Next step: proxy raster preprocessing and model framework prototyping.
