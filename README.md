# Spatial Data Analysis & Heatmap Generation 🗺️📍

## Project Overview
This repository contains a Python-based spatial data analysis project. The script generates an interactive map to visualize real estate points, calculate buffer zones (accessibility radius), and create heatmaps to identify density and hotspots for urban planning.

## Key Features
- **Interactive Mapping:** Utilizes `folium` with an Esri (ArcGIS) basemap layer.
- **Buffer Zone Analysis:** Generates a 1-km radius buffer around a specific point of interest.
- **Conditional Formatting:** Categorizes and color-codes real estate data based on price thresholds using `pandas`.
- **Density Heatmap:** Integrates `folium.plugins.HeatMap` to visualize property density and value hotspots.

## Tech Stack
* **Python**
* **Pandas** (Data manipulation and filtering)
* **Folium** (Geospatial data visualization)

## How to Run
1. Open the `.ipynb` file in **Google Colab** or Jupyter Notebook.
2. Run the cells sequentially. 
3. The final map can be saved as a standalone `.html` file for web presentation.
