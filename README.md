# Mobility-Expansion

This repository supports the "Machine Learning based Multi Modal Transportation Planner" paper published at ASCE ITCD 2024.

**Usage**:
Clone the repository, clear the generated folder as that is where the outputs will accumulate.

**Files & Folders:**
The tl_ folders container tiger line shapefiles for the Census Block Groups

The .csv files contain the US EPA Smart Location Database, filtered for Northern KY and Cincinnati

station_information.json contains data about Red Bike stations.

Main.ipynb contains the code which integrates these data sources and generates tabular output in /generated, as well as Kepler.gl maps within the notebook itself.
