# Threwartha Climate Classification Maps

> ⚠️ **Note:** The classification algorithm, particularly for the Threwartha Climate Classification, is still undergoing refinement and may be subject to minor corrections. However, the overall methodology and all data preprocessing steps are fully documented and explained in the related repository: [Köppen Climate Map Generator](https://github.com/yessimkhanova/koppen_maps).

This repository is part of a broader doctoral research effort and is closely related to the [Köppen Climate Map Generator](https://github.com/yessimkhanova/koppen_maps) project. It presents methods and applications for generating Threwartha Climate Classification maps using Google Earth Engine (GEE) and multiple climate datasets.

## Background

The project is conducted by **Kalamkas Yessimkhanova** under the supervision of **Dr. Matyas Gede** at **Eötvös Loránd University**, Budapest. It focuses on classifying the climate of Kazakhstan and globally using the Threwartha system, complementing the Köppen-based analysis in the related repository.

## Overview of the Köppen Climate Map Generator

The linked [Köppen Climate Map Generator](https://github.com/yessimkhanova/koppen_maps) project uses GEE and various datasets to create Köppen Climate Classification maps. The generation process depends on the source of climate data and follows two distinct approaches:

### 1. **Earth Engine Dataset Collection (ERA5-Land, CMIP6):**
- Update the collection path and band names.
- Modify units and metadata if needed.

### 2. **Uploaded Asset Data (CRU, preprocessed CMIP6):**
- Filter datasets by scenario and time range.
- Adjust band names, units, and metadata.
- Preprocess CMIP6 into ensemble monthly mean temperature and precipitation sum, followed by multiband image creation and classification.

## How to Use

To replicate or modify the climate classification process:
- Load your preferred dataset (Earth Engine or uploaded).
- Adjust script parameters (band names, time range, units).
- Follow preprocessing steps if needed (for CMIP6). See the "Köppen Climate Map Generator" repository
- Run classification logic using the implemented GEE scripts. 

## Credits

This work acknowledges the following datasets and tools:

- **Google Earth Engine**  
  Gorelick et al. (2017). *Google Earth Engine: Planetary-scale geospatial analysis for everyone*. Remote Sensing of Environment.

- **NEX-GDDP-CMIP6**  
  Thrasher et al. (2012). *Bias correcting climate model simulated daily temperature extremes with quantile mapping*. Hydrology and Earth System Sciences, 16(9), 3309-3314.

- **ERA5-Land**  
  Muñoz Sabater, J. (2019). *ERA5-Land monthly averaged data from 1981 to present*. Copernicus CDS. DOI: [10.24381/cds.68d2bb30](https://doi.org/10.24381/cds.68d2bb30)

- **CRU Data**  
  World Bank. *Climate Change Knowledge Portal*. [Link](https://climateknowledgeportal.worldbank.org/). Accessed: 2024.

## Contact

For questions or feedback, please contact:  
**Kalamkas Yessimkhanova**  
📧 kalamkasyessimkhanova@gmail.com
