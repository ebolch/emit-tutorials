# EMIT Tutorials  

Welcome to the EMIT Tutorials repository. This repository stands outside of the main emit-sds functionality. It serves to provide examples for how to use data and code from the EMIT mission, and is part of a collaboration between the LP DAAC, the EMIT team, and the broader community. In the interest of open science this repository has been made public but is still under active development. All jupyter notebooks and scripts should be functional, however, changes or additions may be made. Contributions from all parties are welcome.

These guides, how-tos, and tutorials can also be found in the [EMIT Data Resources Repository](https://github.com/nasa/EMIT-Data-Resources)

---

## EMIT Background  

The [EMIT](https://earth.jpl.nasa.gov/emit/) Project delivers space-based measurements of surface mineralogy of the Earth’s arid dust source regions. These measurements are used to initialize the compositional makeup of dust sources in Earth System Models (ESMs). The dust cycle, which describe the generation, lofting, transport, and deposition of mineral dust, plays an important role in ESMs.  Dust composition is presently the largest uncertainty factor in quantifying the magnitude of aerosol direct radiative forcing.  By understanding the composition of mineral dust sources, EMIT aims to constrain the sign and magnitude of dust-related radiative forcing at regional and global scales. During its one-year mission on the International Space Station (ISS), EMIT will make measurements over the sunlit Earth’s dust source regions that fall within ±52° latitude. EMIT will schedule up to five visits (three on average) of each arid target region and only acquisitions not dominated by cloud cover will be downlinked. EMIT-based maps of the relative abundance of source minerals will advance the understanding of the current and future impacts of mineral dust in the Earth system.  

EMIT Data Products are distributed by the [LP DAAC](https://lpdaac.usgs.gov/). Learn more about EMIT data products from [EMIT Product Pages](https://lpdaac.usgs.gov/product_search/?query=emit&status=Operational&view=cards&sort=title) and search for and download EMIT data products using [NASA EarthData Search](https://search.earthdata.nasa.gov/search?q=%22EMIT%22)

---

## Prerequisites/Setup Instructions

This repository requires that users set up a compatible Python environment and download the EMIT granules used. See the `setup_instuctions.md` file in the `./setup/` folder.

## Repository Contents  

### **Guides**  

+ Getting EMIT Data using EarthData Search - A thourough walkthrough for using [EarthData Search](https://search.earthdata.nasa.gov/search) to find and download EMIT data.

### **How-To Notebooks**

+ How to Convert to ENVI Format - Convert from downloaded netCDF4 (.nc) format to .envi format.
+ How to Orthorectify - Use the geometry lookup table (GLT) included with the EMIT netCDF4 file to project on a geospatial grid (EPSG:4326).
+ How to Extract Point Data  - Extract spectra using lat/lon coordinates from a .csv and build a dataframe/.csv output.
+ How to Extract Area Data - Clip to/extract an area defined by a .geojson or shapefile.
+ How to use EMIT Quality Data - Build a mask using bands from  an EMIT L2A Mask file and apply it to an L2A Reflectance file.

### **Tutorial Notebooks**  

+ Exploring EMIT L2A Reflectance  

---

## Helpful Links  

+ [EMIT Website](https://earth.jpl.nasa.gov/emit/)  

+ [EMIT Github Repository](https://github.com/emit-sds) - Main EMIT Repository  

+ [EMIT Utilities Github Repository](https://github.com/emit-sds/emit-utils) - General convenience utilities for working with EMIT data

+ [L2A Reflectance User Guide](https://lpdaac.usgs.gov/documents/1569/EMITL2ARFL_User_Guide_v1.pdf)  

+ [L2A Algorithm Theoretical Basis Document](https://lpdaac.usgs.gov/documents/1571/EMITL2A_ATBD_v1.pdf)  

+ [EMIT LP DAAC Product Pages](https://lpdaac.usgs.gov/product_search/?query=emit&status=Operational&view=cards&sort=title) - Learn more about available EMIT products  

+ [EMIT on Earth Data Search](https://search.earthdata.nasa.gov/search?q=%22EMIT%22) - Find EMIT Data  

---

## Contact Info:  

Email: LPDAAC@usgs.gov  
Voice: +1-866-573-3222  
Organization: Land Processes Distributed Active Archive Center (LP DAAC)¹  
Website: <https://lpdaac.usgs.gov/>  
Date last modified: 01-09-2023  

¹Work performed under USGS contract G15PD00467 for NASA contract NNG14HH33I.  
