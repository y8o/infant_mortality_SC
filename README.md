# Mapping Infant Mortality in South Carolina

<p align="center">
  <img src="./imr_sc.png" alt="Infant Mortality in South Carolina" width="600"/>
</p>
<p align="center">
  <img src="./pop_perc.png" alt="Infant Mortality in South Carolina" width="600"/>
</p>

This GIS project visualizes public health and demographic data at the county level across South Carolina. Using 2010 U.S. Census data and infant mortality records from SC DHEC, the project creates a series of dot density and choropleth maps, including an inset map of health regions. The maps reveal important correlations between racial demographics and health outcomes, particularly highlighting disparities in infant mortality rates across different communities.

---

## Project Objectives

- Join census population tables to county shapefiles
- Create dot density and choropleth maps using normalized data
- Visualize infant mortality rates and regional health boundaries
- Practice map layout design with titles, scale, north arrow, and inset maps
- Use `Convert Legend to Graphics` to customize legends

---

## Tools and Technologies

- **ArcGIS Desktop**
- **Spatial Analyst**
- **Table Joins**
- **Dot Density Mapping**
- **Choropleth Mapping**
- **Inset Mapping with Multiple Data Frames**
- **Convert Legend to Graphics**
- **Projection Used**: NAD 1983 UTM Zone 17N (meters)

---

## Health and Demographic Maps

### 1. Racial Demographics Map

- Created a **choropleth map** showing the percentage of a selected racial group by county.
- Population data normalized by total county population.
- Values formatted as percentages with 2 decimal places.
- Classification: 5-class scheme using Natural Breaks or Quantile.
- Elements included:
  - Title
  - North arrow
  - Scale bar
  - Data source: 2010 U.S. Decennial Census
  - Custom legend using converted graphics

### 2. Infant Mortality Rate Map

- Visualizes **Infant Mortality Rate (IMR)** data from 2004–2008.
- Choropleth map using direct rates (not normalized).
- Inset map added for SC DHEC health regions.
- Text box notes:
  - Map author, date
  - Projection and data sources
  - Disclaimer: 18 births excluded due to unknown county of origin

---

## Key Findings

- Counties with the **highest percentage of Black or African American populations** are concentrated in the central and eastern parts of the state.
- **Infant mortality rates** varied significantly across counties, with some rural areas showing higher rates than urban centers.
- **Dot density mapping** provided intuitive visuals for raw population counts, while **normalized choropleth maps** revealed relative densities and disparities.

## Race and Infant Mortality Analysis

The analysis reveals significant correlations between racial demographics and health outcomes in South Carolina:

- Counties with higher percentages of Black or African American populations show elevated infant mortality rates
- This pattern suggests persistent health disparities that may be influenced by:
  - Limited access to healthcare facilities in rural areas
  - Socioeconomic factors affecting maternal and infant health
  - Historical and systemic barriers to healthcare access
- The visualization of these patterns through both dot density and choropleth mapping helps identify areas that may require targeted healthcare interventions and resources

---

## Date

September 2023  
Created by: Oscar Babin
