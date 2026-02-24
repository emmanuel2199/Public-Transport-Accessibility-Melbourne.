# Evaluating Public Transport Accessibility in Melbourne

## Project Overview

This project analyses the accessibility of key landmarks across Melbourne using public transport data (bus stops, tram stops, and train stations).

The objective was to:

- Measure proximity of landmarks to transport infrastructure  
- Develop an accessibility index  
- Identify underserved locations  
- Propose data-driven transport improvements  

This case study simulates a real-world city planning scenario using real City of Melbourne open datasets.

---

## Technologies Used

- Python  
- Pandas & NumPy  
- GeoPandas  
- Scikit-learn (KMeans Clustering)  
- Folium (Geospatial Visualisation)  
- Matplotlib & Seaborn  
- Plotly (3D Visualisation)  
- Haversine Distance Calculation  

---

## Dataset Sources

- City of Melbourne Open Data API  
- Landmarks dataset  
- Bus stop dataset  
- Tram stop dataset  
- Train station dataset  
- Pedestrian count dataset  

---

## Methodology

### 1️. Data Cleaning & Preprocessing

- Parsed geospatial coordinate columns  
- Converted data types  
- Handled missing values  
- Structured datasets for spatial analysis  

### 2️. Feature Engineering

- Calculated nearest transport distances using the Haversine formula  
- Created an **Accessibility Index** weighted by:
  - Bus proximity  
  - Tram proximity  
  - Train proximity  

### 3️. Exploratory Data Analysis (EDA)

- Correlation heatmaps  
- Pairplots  
- Distance distribution analysis  
- Accessibility score exploration  

### 4️. Spatial & Cluster Analysis

- Heatmap visualisation of accessibility levels  
- KMeans clustering to group landmarks by accessibility  
- Identification of poorly connected areas  

---

## Key Insights

- Landmarks near Melbourne CBD demonstrate the highest accessibility  
- Outer suburbs show lower public transport connectivity  
- Cluster analysis clearly identified under-served regions  
- Multiple landmarks were recommended for new bus stop placements  

---

## Visualisations

### Accessibility Heatmap
![Accessibility Heatmap](images/heatmap.png)

### Cluster Analysis
![Cluster Analysis](images/cluster.png)

### Correlation Heatmap
![Correlation Heatmap](images/correlation.png)

---

## Business Impact

This project demonstrates how data analytics and spatial modelling can:

- Support urban infrastructure planning  
- Identify public transport coverage gaps  
- Inform evidence-based policy decisions  
- Optimise transport accessibility for residents and visitors  

---
