# Evaluating Public Transport Accessibility to Places of Interest in Melbourne

## Project Overview

This project evaluates how accessible public transport is to major landmarks across Melbourne.  
Using geospatial data and statistical analysis, the study identifies areas with strong transport connectivity and areas that require infrastructure improvement.

The project combines **data analysis, geospatial techniques, and clustering methods** to generate insights into Melbourne’s public transport accessibility.

---

## Project Preview

This project analyses accessibility to:

- Train stations
- Tram stops
- Bus stops
- Major places of interest

The analysis produces accessibility scores and clusters landmarks based on transport availability.

---

## Technologies Used

**Programming Language**

- Python

**Libraries**

- Pandas
- NumPy
- Matplotlib
- GeoPandas
- Folium
- Scikit-learn
- Plotly

**Tools**

- Jupyter Notebook
- Git
- GitHub

---

## Data Sources

Data was obtained from the **City of Melbourne Open Data Portal**.

Datasets include:

- Places of interest
- Bus stop locations
- Tram stop locations
- Train station locations
- Pedestrian network data

---

## Methodology

### Data Collection
Public transport datasets were collected from the Melbourne open data API.

### Data Cleaning
Datasets were cleaned and transformed into geospatial format using latitude and longitude coordinates.

### Distance Calculation
Distances between landmarks and transport stops were calculated using the **Haversine formula**.

### Accessibility Index
An **Accessibility Index** was developed based on proximity to:

- Bus stops
- Tram stops
- Train stations

### Clustering
K-Means clustering was applied to group landmarks into accessibility categories.

### Visualisation
Geospatial visualisations and correlation analysis were created to identify accessibility patterns.

---

## Key Findings

- Landmarks near the **Melbourne CBD** have the highest transport accessibility.
- Outer suburban locations show lower accessibility scores.
- Several areas could benefit from improved public transport coverage.

---

## Project Report

The full analysis including visualisations and outputs can be viewed here:

[View Project Report](melbourne_public_transport_accessibility_report.pdf)

---

## Repository Structure

```
Public-Transport-Accessibility-Melbourne
│
├── README.md
├── melbourne_public_transport_accessibility_analysis_report.pdf
│
└── notebooks
    └── transport_accessibility_analysis.ipynb
```

---

## Author

**Emmanuel Clement Anthony**  
Master of Data Science  
Melbourne, Australia

GitHub: https://github.com/emmanuel2199
