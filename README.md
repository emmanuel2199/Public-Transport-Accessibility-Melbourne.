# Evaluating Public Transport Accessibility to Places of Interest in Melbourne

## Project Overview
This project analyses the accessibility of public transport infrastructure to key landmarks across Melbourne. The goal is to evaluate how easily residents and visitors can reach important places of interest using public transport such as buses, trams, and trains.

By analysing spatial data and transport networks, the project identifies areas that are well served by public transport and highlights locations where accessibility can be improved.

The analysis combines geospatial analysis, statistical methods, clustering, and visualisation techniques to derive insights and propose recommendations for improving transport connectivity.

---

## Objectives

The main objectives of this project are:

- Assess the accessibility of public transport to key landmarks in Melbourne
- Calculate distances between landmarks and transport stops
- Develop an Accessibility Index to quantify ease of access
- Identify areas with poor public transport coverage
- Use clustering techniques to group landmarks based on accessibility
- Provide data-driven recommendations for improving transport infrastructure

---

## Data Sources

The datasets used in this project were obtained from **City of Melbourne Open Data**.

Datasets include:

- Landmarks and Places of Interest
- Bus Stops
- Tram Stops
- Train Stations
- Pedestrian Counting System Data

These datasets provide geospatial coordinates used to analyse accessibility patterns across Melbourne.

---

## Technologies Used

### Programming Language
- Python

### Libraries
- Pandas
- NumPy
- Matplotlib
- GeoPandas
- Folium
- Scikit-learn
- Plotly
- Requests

These libraries were used for data cleaning, geospatial analysis, clustering, and visualisation.

---

## Methodology

### 1. Data Collection
Data was retrieved from the **City of Melbourne Open Data API**, including information on landmarks, bus stops, tram stops, and train stations.

### 2. Data Cleaning and Preparation
The datasets were cleaned and processed to ensure consistency. Coordinate values were extracted and converted into latitude and longitude.

### 3. Distance Calculation
The **Haversine formula** was used to calculate distances between landmarks and the nearest transport stops.

### 4. Accessibility Index
An Accessibility Index was created to measure how easily each landmark can be accessed using public transport.

The index combines proximity to:
- Bus Stops
- Tram Stops
- Train Stations

Higher scores indicate better accessibility.

### 5. Exploratory Data Analysis
Several visualisations were created to understand spatial patterns including:

- Scatter plots
- Correlation heatmaps
- Pair plots

### 6. Clustering Analysis
K-Means clustering was applied to group landmarks based on accessibility levels. This helped identify well-connected and poorly connected locations.

### 7. Spatial Visualisation
Interactive maps were generated using **Folium** to visualise accessibility patterns across Melbourne.

---

## Key Findings

### Transport Accessibility Patterns
Landmarks located near the **Melbourne CBD** show the highest accessibility levels. Outer suburban areas tend to have lower accessibility scores.

### Clustering Insights
Three clusters of landmarks were identified:

- High Accessibility – Well served by multiple transport modes
- Moderate Accessibility – Reasonable transport access
- Low Accessibility – Limited public transport coverage

### Areas Needing Improvement
Several locations were identified as having poor public transport accessibility and could benefit from improved transport infrastructure.

---

## Recommendations

Based on the analysis, the following improvements are recommended:

- Introduce new bus stops near poorly connected landmarks
- Improve transport service coverage in outer areas
- Monitor pedestrian traffic to prioritise infrastructure upgrades
- Continue evaluating accessibility using updated datasets

These actions could significantly improve connectivity and accessibility across Melbourne.

---

## Future Work

Potential future improvements include:

- Incorporating real-time transport data
- Predicting transport demand using machine learning
- Using travel time analysis instead of only distance
- Integrating pedestrian movement data

---

## Author

**Emmanuel Clement Anthony**  
Master of Data Science  
Melbourne, Australia
