# Biodiversity Intactness Index change in Phoenix, AZ
<img src="https://assets.simpleviewinc.com/simpleview/image/upload/c_limit,q_75,w_1200/v1/crm/phoenix/14583_7179_69160001_b9b9dc10-5056-b3a8-49bff22bfd5a2876.jpg" alt="maricopa county scenery" width="800"/>

Image credits: [Visit Phoenix](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.visitphoenix.com%2Flisting%2Fmaricopa-county-parks-%2526-recreation-department%2F1216%2F&psig=AOvVaw2YO5ZXwc20MlaxKqS2zy6-&ust=1733524430093000&source=images&cd=vfe&opi=89978449&ved=0CBQQjRxqFwoTCJDYw_fXkYoDFQAAAAAdAAAAABAE)

## About 

In 2021, Maricopa County —home to the Phoenix metropolitan area— was identified as the U.S. county with the most significant increase in developed land since 2001 [1]. This rapid urban sprawl has profound implications for biodiversity and the health of surrounding natural ecosystems. In this repository, I investigate the impacts of urban expansion by analyzing a dataset that captures values for the Biodiversity Intactness Index (BII) [2]. The Biodiversity Intactness Index (BII) measures biodiversity change using abundance data on plants, fungi and animals worldwide. The BII shows how local terrestrial biodiversity responds to human pressures such as land use change and intensification [3]. Using Python, I examine changes in BII in the Phoenix county subdivision area between 2017 and 2020, shedding light on how urban growth affects biodiversity over time. 

## Repository structure

```
phoenix-bii-change
├──  .gitignore
├──  README.md
└──  phoenix-bii-change.ipynb
```
`phoenix-bii-change.ipynb` contains all of the code and final outputs for my analysis.

## Data

**Biodiversity Intactness Index (BII) Time Series:** I access the io-biodiversity collection from the Microsoft Planetary Computer STAC catalog using an API. In my analysis, I use the 2017 and 2020 rasters covering the Phoenix subdivision.


**Phoenix Subdivision Shapefile:** I use a shapefile containing county boundary lines from the U.S. Census Bureau. To access, visit the link below and download the file `tl_2022_04_cousub.shp` to a data folder.




## References

#### Literature

- [1]   Z. Levitt and J. Eng, “Where America’s developed areas are growing: ‘Way off into the horizon’,” The Washington Post, Aug. 2021, Available: https://www.washingtonpost.com/nation/interactive/2021/land-development-urban-growth-maps/ [Accessed: Nov. 22, 2024]
- [2]   F. Gassert, J. Mazzarello, and S. Hyde, “Global 100m Projections of Biodiversity Intactness for the years 2017-2020 [Technical Whitepaper].” Aug. 2022. Available: https://ai4edatasetspublicassets.blob.core.windows.net/assets/pdfs/io -biodiversity/Biodiversity_Intactness_whitepaper.pdf
- [3]   Measurement of Biodiversity. (2024, 16 November). In Wikipedia. https://en.wikipedia.org/wiki/Measurement_of_biodiversity

#### Data sets
- Microsoft Planetary Computer data catalogue (2024), io-biodiversity Collection [Data set] Available from: https://planetarycomputer.microsoft.com/dataset/io-biodiversity. Access date: December 3, 2024.
- U.S. Census Bureau. (2022). “tl_2022_04_cousub”, TIGER/Line Shapefiles. https://www.census.gov/cgi-bin/geo/shapefiles/index.php?year=2022&layergroup=County+Subdivisions. Access date: December 3, 2024.


## Acknowledgements

This repository was created as the final assignment for the graduate course EDS 220: Working with Environmental Datasets in the [Masters of Environmental Data Science (MEDS) program](https://bren.ucsb.edu/masters-programs/master-environmental-data-science), taught by [Dr. Carmen Galaz García](https://github.com/carmengg).

