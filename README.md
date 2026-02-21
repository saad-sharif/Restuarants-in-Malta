# Restaurants in Malta

## Project Overview

In this project, we aim to identify the **ideal location for opening a new restaurant in Malta** using data analytics techniques.  
The target audience for this analysis includes **potential stakeholders and investors** interested in expanding their restaurant business abroad.

The main objective is to shortlist areas that are likely to **maximize restaurant performance**, measured through:
- Customer ratings
- Number of likes / popularity

Several factors influence restaurant success. This project specifically explores whether:
- **Population density**
- **Proximity to historic sites**

have any relationship with restaurant performance across Malta.

---

## Objectives

- Collect restaurant venue data across Malta using the **Foursquare API**
- Analyze geographic and popularity patterns
- Identify clusters of high-performing restaurant areas
- Provide data-driven location recommendations to stakeholders

---

## Data Sources

- **Foursquare API** – restaurant venue data, ratings, likes
- **Geographic coordinates** – latitude and longitude grids covering Malta (including Gozo)

---

## Technologies & Libraries Used

This project is implemented in **Python** and relies on the following libraries:

### Core Data & Analysis
- pandas  
- numpy  
- csv  
- requests  

### Visualization
- matplotlib  
- seaborn  
- folium  
- branca.colormap  

### Geospatial
- geopy (Nominatim)

### Machine Learning
- scikit-learn  
  - KMeans (clustering)
  - LinearRegression
ts
