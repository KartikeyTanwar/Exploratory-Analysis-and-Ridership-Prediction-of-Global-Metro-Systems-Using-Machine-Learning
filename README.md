# Exploratory-Analysis-and-Ridership-Prediction-of-Global-Metro-Systems-Using-Machine-Learning

* This study explores how infrastructure characteristics (stations, lines, length) and demographic characteristics (population and population density) influence ridership.
* Goal: Creating a model to predict annual ridership of metro systems and to analyze the contribution of different features in prediction of annual ridership.

# Tools and Libraries Used

The following tools and libraries were used throughout the project:
  * Python for scripting and modeling
  * pandas, numpy for data manipulation
  * scikit-learn for Random Forest and model evaluation
  * xgboost for gradient boosting
  * matplotlib, seaborn for visualization
  * osmnx, folium for map generation
  * BeautifulSoup for web scraping
 
# METHODOLOGY

## Data Collection

* Source: Publicly available websites (primarily Wikipedia)
* Method: Web scraping using Python with requests, BeautifulSoup, and pandas
* Dataset: 209 cities with operational metro systems
* Collected Attributes:
  * City name & country
  * Number of stations
  * Number of lines
  * System length (km)
  * Annual average ridership (millions)
  * Population (millions)
  * Population density (people/sq. km)

## Data Visualization with OpenStreetMap

* Objective: Provide spatial context for metro infrastructure.
* Tools Used:
  * OpenStreetMap (OSM) data
  * OSMNX for data extraction
  * Folium for interactive map visualization
* Process:
  * Extracted metro station nodes in selected cities
  * Plotted interactive maps showing Stations and network connectivity on the map
* Purpose: Visually enhance and support the statistical analysis

<img width="2625" height="1287" alt="image" src="https://github.com/user-attachments/assets/c80bb262-c523-49ac-87e4-5e6ba3d67a6d" />

# Results

Model Performance

<img width="1739" height="311" alt="image" src="https://github.com/user-attachments/assets/6db1f44b-6ba8-430e-9238-40cdd36c9634" />

<img width="2312" height="1298" alt="image" src="https://github.com/user-attachments/assets/5645e20f-36a9-423a-b44d-aed2a199fce2" />

<img width="2511" height="1325" alt="image" src="https://github.com/user-attachments/assets/1ac6e905-4ad7-4912-8b3d-2920cc77f811" />

