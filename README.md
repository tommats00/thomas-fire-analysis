### Analysis of the 2017 Thomas Fire

Author: Tom Gibbens-Matsuyama (tommats00\@github.io)

<img src="https://camo.githubusercontent.com/eb96c7e74feb1cad555d796e03bf71e25a4f38058ba619e1e4da5c6a8d86330d/68747470733a2f2f7777772e6c6965666663616272617365722e636f6d2f77702d636f6e74656e742f75706c6f6164732f77696c64666972652d736c6964652d3530302e6a7067" alt="Thomas Fire 2017">

Image Credits: Carsten Shertzer \| Getty Images

# About

### Purpose

In December of 2017, one of California's largest wildfires burned over 280,000 acres of land in Ventura and Santa Barbara counties. The purpose of this analysis is to do the following: visualize how the Air Quality Index (AQI) was effected in Santa Barbara County and produce a false color image containing the Thomas Fire boundary.

### Highlights of analysis:

-   Use `pandas` to read in tabular data
-   Use `rioxarray` and `geopandas` to read in spatial data
-   Read data from a link and local source
-   Filter and transform tabular data types with `pandas`
-   Filter and transform spatial data with `rioxarray` and `geopandas`
-   Visualize filtered AQI data
-   Visualize filtered landsat and boundary data

## Dataset descriptions:

#### AQI Data

[AQI data](https://www.airnow.gov/aqi/aqi-basics/) from the [US Environmental Protection Agency (EPA)](https://www.epa.gov/) will be used to visualize the impact of the 2017 Thomas Fire in Santa Barbara County. This data comes from these [pre-generated data files](https://aqs.epa.gov/aqsweb/airdata/download_files.html). These files are updated twice a year, once in June to capture the entire previous year and once in December to capture the Summer.

#### Landsat Collection 2 Level-2 data from Landsat 8

This dataset is a collection of bands from the Landsat Collection 2 Level-2 collected by the Landsat 8 satellite. This data was taken from the [Microsoft Planetary Computer data catalogue](https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2) and pre-processed for our use.

#### California Fire Perimeters

The second dataset is a pre-processed geospatial data frame from [Data.gov](https://catalog.data.gov/dataset/california-fire-perimeters-all-b3436). This dataset contains the Thomas Fire perimeter data.

## References & data sources

AQI Data: Available from: (https://aqs.epa.gov/aqsweb/airdata/download_files.html#AQI.) Access date: October 23, 2024

Microsoft Planetary Computer Data Catalogue, Landsat collection 2 Level-2. Available from: (https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2.) Access date: November 19, 2024.

Data.gov Data Catalogue, California Fire Perimeters (all). Available from: (https://catalog.data.gov/dataset/california-fire-perimeters-all-b3436.) Access date: November 19, 2024.

#### Ackowledgements
Materials created by [Carmen Galaz-Garcia](https://github.com/carmengg) for EDS-220: [Working with Environmental Data](https://meds-eds-220.github.io/MEDS-eds-220-course/)
