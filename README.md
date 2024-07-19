# Bike Ride Data Analysis
This repository contains two Jupyter notebooks focused on analyzing bike ride data. The analysis includes data preprocessing, filtering, and visualization using Folium maps.

## Notebooks

### 1. Electric Bike Data Analysis (`electric.ipynb`)
This notebook focuses on processing and visualizing data specific to electric bikes.

**Steps:**
1. **Load Data:** The dataset is loaded from a CSV file.
2. **Data Cleaning:** Unnecessary columns are removed, and rows with certain bike types (classic_bike and docked_bike) are excluded.
3. **Duplicate Removal:** Duplicate rows based on start coordinates are removed.
4. **Sampling:** A random sample of 1700 data points is selected for visualization.
5. **Visualization:** A Folium map is created to display the locations of the selected bike rides.
6. **Output:** `electric_map_final.html`

### 2. Classic Bike Data Analysis (`classic.ipynb`)
This notebook focuses on processing and visualizing data specific to classic bikes.

**Steps:**
1. **Load Data:** The dataset is loaded from a CSV file.
2. **Data Cleaning:** Unnecessary columns are removed, and rows with certain bike types (electric_bike and docked_bike) are excluded.
3. **Duplicate Removal:** Duplicate rows based on start coordinates are removed.
4. **Sampling:** A random sample of 1700 data points is selected for visualization.
5. **Visualization:** A Folium map is created to display the locations of the selected bike rides.
6. **Output:** `classic_map_final.html`

## Files
- `electric.ipynb`: Jupyter notebook for electric bike data analysis.
- `classic.ipynb`: Jupyter notebook for classic bike data analysis.
- `electric_map_final.html`: HTML file containing the map visualization for electric bikes.
- `classic_map_final.html`: HTML file containing the map visualization for classic bikes.
