# MLFC
Machine Learning Foundations Course by Prof. Neil Lawrence

---

# Poverty and Literacy Levels Correlation in Kenya

This repository contains a Jupyter/Colab notebook exploring the relationship between literacy rates and poverty measures across counties in Kenya using geospatial and socioeconomic data for 2019. The analysis covers Kenya’s primary and secondary school distribution, population mapping, and the quantitative link between literacy rates and poverty in Kenya. Understanding how poverty and education outcomes relate spatially across Kenya's 47 counties is critical for policy interventions. By visualizing and modeling these indicators, we can better identify priority regions, investigate causes, and inform decisions.

## Datasets Used

- **Population by County (KNBS 2019 Census)**  
  Source: [KNBS](https://www.knbs.or.ke/wp-content/uploads/2023/09/2019-Kenya-population-and-Housing-Census-Volume-1-Population-By-County-And-Sub-County.pdf)  
  CSV: [`kenya_population_by_county_2019.csv`](https://raw.githubusercontent.com/call493/MLFC/main/kenya_population_by_county_2019.csv)

- **School Locations**  
  Source: [EnergyData Kenya Schools 2020](https://energydata.info/dataset/kenya-schools)  
  JSON: [`schools.json`](https://raw.githubusercontent.com/call493/MLFC/main/schools.json)  
  Shapefile ZIP: [`schools.zip`](https://github.com/call493/MLFC/raw/main/schools.zip)

- **County Boundaries (GeoBoundaries)**  
  GeoJSON: [`geoBoundaries-KEN-ADM1.geojson`](https://github.com/wmgeolab/geoBoundaries/raw/9469f09/releaseData/gbOpen/KEN/ADM1/geoBoundaries-KEN-ADM1.geojson)

- **Literacy Rates by County (KNBS 2019)**  
  CSV: [`kenya_literacy_2019.csv`](https://raw.githubusercontent.com/call493/MLFC/main/kenya_literacy_2019.csv)

- **Poverty Rates by County (KNBS 2019)**  
  Poverty Report: [KNBS](https://www.knbs.or.ke/wp-content/uploads/2023/09/The-Kenya-Poverty-Report-2019.pdf)  
  CSV: [`kenya_poverty_2019.csv`](https://raw.githubusercontent.com/call493/MLFC/main/kenya_poverty_2019.csv)

## Main Features

- Plotting and mapping Kenya’s county boundaries with population heatmaps (matplotlib, folium).
- Visualizing primary vs. secondary school distribution by county.
- Merging and normalizing county names across multiple datasets.
- Creating combined maps showing population, school locations (public vs private), and overlays.
- Merging literacy and poverty rates for county-level analysis.
- Statistical correlation analysis (Pearson, Spearman).
- Multivariate regression to test predictors of literacy.
- Outlier identification and discussion of collinearity issues.

No local configuration needed—just open in Colab.
