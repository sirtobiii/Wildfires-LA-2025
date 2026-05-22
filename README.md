# Interactive Wildfire Mapping in Los Angeles, California in January 2025 **

This project visualizes the extent and the timely dynamics of the January 2025 wildfires in Los Angeles, CA, and identifies the counties most affected.

## Objective
The goal of this project is to create an interactive map with the Folium package that illustrates the intensity and heat of the wildfires for each day, respectively. 
Additionally, a choropleth map will indicate which counties around Los Angeles were most affected by intense wildfire occurrances.

## Data Sources
* **NASA FIRMS Earth Data:** Satellite image derived wildfire data for Los Angeles, CA in January 2025, stored in a CSV-table.
* **County Boundaries:** A vector county layer provided by the California State Geoportal.

## Reproducing the Environment
This project requires a specific spatial software stack. To recreate the environment:
1. Ensure you have Conda installed.
2. Run: `conda env create -f environment.yml`
3. Activate: `conda activate sds-env`

## Usage
Execute the Jupyter Notebook `Wildfires_LA.ipynb` from top to bottom. 

## Output Data
Interactive Folium map that shows the detected wildfires and includes a timeslider to visualize the timely dynamics.
Maps of Wildfire counts can be exported to `outputs/maps/` if wished.