# raster-images-to-vector-polygons

The purpose of this repository is to document the processes of converting raster data to vector polygons to be used within maps for evaluation purposes.

This repository contains a Python Jupyter notebook to process National Land Cover Database raster data into vector polygons. The workbook automates several shell commands along with processes to add json properties to the geojson file to present the geojson data using [ipyleaflet](https://ipyleaflet.readthedocs.io/en/latest/index.html).

The repository also contains a Leaflet map (index.html) that allows for further evaluation of the data in a larger format than ipyleaflet provides within the notebook.

#### Data Source
The raster data for this notebook were downloaded from the [Multi-Resolution Land Characteristics (MRLC) Consortium](https://www.mrlc.gov) website.
The MRLC website contains a tool called [MRLC NLCD Viewer](https://www.mrlc.gov/viewer/). It provides the ability to select a region of the United States along with the types of land cover raster data to download.

#### Environment Setup
Prior to running the Jupyter notebook, a Python environment must be created. The following are the Conda commands I used to create an environment and install the needed libraries.
 
conda install python geopandas pandas numpy jupyterlab geojson ipyleaflet

#### Leaflet Map
A larger map version `index.html` is available for more close evaluation than provided in the notebook.

#### Other data downloads in the sources folder  
These files can be plugged into the cells above to analyze land cover in other areas

| Download Name  |      Tiff File Name      |  
|----------|:-------------:  
NLCD_Jacksonville_area.zip | NLCD_2019_Land_Cover_L48_20210604_v1AdZOChAH6SMKC8JfEn.tiff
NLCD_Sanibel_area.zip | NLCD_2019_Land_Cover_L48_20210604_98Ejuh2wAV8IMNpUssoI.tiff
NLCD_Punta_Gorda_area.zip | NLCD_2019_Land_Cover_L48_20210604_6Ryotb4ak7ugzjap47E4.tiff
#### [National Land Cover Database Class Legend and Descriptions](https://www.mrlc.gov/data/legends/national-land-cover-database-class-legend-and-description)


