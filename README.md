# Bangkok-UHI-ECOSTRESS

## Project Overview

This repository contains the datasets, processing workflow, maps, visualizations, and analytical outputs developed for the MSc dissertation:

**"Spatio-Temporal Analysis of Urban Thermal Variability and Surface Urban Heat Island Dynamics in Bangkok Using ECOSTRESS Data"**

The study investigates the spatial distribution of Land Surface Temperature (LST) and Surface Urban Heat Island (SUHI) intensity across Bangkok Metropolitan Administration (BMA), Thailand, using NASA ECOSTRESS thermal observations. The research integrates Local Climate Zone (LCZ) classification, vegetation indices, built-up indices, and urban morphology indicators to evaluate the influence of urban form on thermal patterns during heatwave conditions.

---
## Project Workflow

```text
ECOSTRESS Data
      ↓
Quality Control
      ↓
LST Extraction
      ↓
LCZ Mapping (Google Earth Engine)
      ↓
NDVI / NDBI Generation
      ↓
Urban Morphology Indicators
      ↓
Statistical Analysis
      ↓
Surface Urban Heat Island (SUHI) Assessment

## Research Objectives

- Analyze spatial variability of Land Surface Temperature (LST) across Bangkok.
- Quantify Surface Urban Heat Island (SUHI) intensity using Local Climate Zones (LCZs).
- Examine relationships between vegetation cover, built-up intensity, urban morphology, and thermal conditions.
- Assess the influence of urban landscape characteristics on heat distribution during heatwave events.
- Demonstrate the application of ECOSTRESS thermal observations for urban climate studies.

---

## Study Area

The study was conducted within the Bangkok Metropolitan Administration (BMA), Thailand, one of Southeast Asia's largest and fastest-growing megacities.

Bangkok experiences rapid urbanization, high population density, extensive impervious surfaces, and increasing vulnerability to urban heat stress. These characteristics make the city an ideal case study for investigating Surface Urban Heat Island dynamics and thermal variability.

Study area maps and Local Climate Zone classifications are available in the **Figures** directory.

---

## Datasets Used

### Thermal Data

- NASA ECOSTRESS Level 2 Land Surface Temperature and Emissivity (L2 LSTE)

### Urban Classification

- Local Climate Zone (LCZ) map generated using Google Earth Engine

### Vegetation and Built-up Indicators

- Sentinel-2 imagery
- NDVI (Normalized Difference Vegetation Index)
- NDBI (Normalized Difference Built-up Index)

### Urban Morphology Indicators

- Google Open Buildings Dataset
- Building Height
- Building Surface Fraction (BSF)

### Ancillary Datasets

- ESA WorldCover
- OpenStreetMap (OSM)
- Copernicus DEM

---

## Methodology

### 1. Local Climate Zone Mapping

- Training polygons were manually digitized in Google Earth Engine.
- Supervised classification was performed to generate LCZ classes.
- LCZ maps were used for SUHI assessment and thermal comparison.

### 2. ECOSTRESS Processing

- Acquisition of ECOSTRESS L2 LSTE products.
- Quality assessment and filtering of scenes.
- Extraction and preprocessing of Land Surface Temperature data.
- Conversion and visualization of thermal datasets.

### 3. Spatial Indicator Generation

- NDVI generation from Sentinel-2 imagery.
- NDBI generation from Sentinel-2 imagery.
- Building Height and Building Surface Fraction mapping.

### 4. Statistical Analysis

- LST–NDVI relationship analysis.
- LST–NDBI relationship analysis.
- Correlation analysis among thermal and environmental indicators.
- LCZ-wise comparison of thermal characteristics.

---

## Key Outputs

The repository contains:

- Study Area Maps
- Local Climate Zone Maps
- ECOSTRESS LST Maps
- NDVI Maps
- NDBI Maps
- Building Height Maps
- Building Surface Fraction Maps
- Statistical Analysis and Correlation Visualizations

All figures are available in the **Figures** directory.

---
## Key Findings

- Surface Urban Heat Island (SUHI) intensity varied across Local Climate Zones.
- Built-up areas exhibited higher Land Surface Temperature compared to vegetated areas.
- Vegetation cover showed a cooling influence on urban thermal conditions.
- Urban morphology influenced the spatial distribution of heat across Bangkok.
- ECOSTRESS observations proved effective for analysing urban thermal variability during heatwave conditions.

## Software and Tools

- Google Earth Engine (GEE)
- QGIS
- Python
- ECOSTRESS Data Products
- ESA WorldCover
- OpenStreetMap
- Google Open Buildings Dataset
- Copernicus DEM

---

## Repository Structure

```text
Bangkok-UHI-ECOSTRESS/
│
├── Figures/
│   ├── Study Area Maps
│   ├── LCZ Maps
│   ├── ECOSTRESS LST Maps
│   ├── NDVI Maps
│   ├── NDBI Maps
│   ├── Urban Morphology Maps
│   └── Statistical Analysis Outputs
│
└── README.md
```

---

## Author

**Tulika Moulik**

M.Sc. Environmental Science  
Department of Botany  
Banaras Hindu University (BHU)

Research Interests:
- Urban Climate
- Remote Sensing
- GIS
- Urban Heat Island Studies
- Environmental Data Analysis
