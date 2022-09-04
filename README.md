# Generate Heatmap using Datashader in Python and serve the heatmap tiles in OpenLayers map
Before generating  the heatmap, we will set up conda environment and install required python GIS packages for this task. Make sure conda is installed on your system. Use following commands to create a conda environment and to install python libraries. When you install geocube library using conda, it will automatically install related dependencies that includes gdal, shapely, rasterio, geopandas, xarray, rioxarray etc. After that, will install datashader.
And we will also install pygeos library which is used to speed up the vectorized operations in GeoPandas and Shapely.
```
(base) geoknight@pop-os:~$conda create -n spatial-dev.guru python=3.10
(base) geoknight@pop-os:~$conda activate spatial-dev.guru
(spatial-dev.guru) geoknight@pop-os:~$conda install -c conda-forge geocube
(spatial-dev.guru) geoknight@pop-os:~$conda install -c conda-forge datashader
(spatial-dev.guru) geoknight@pop-os:~$conda install -c conda-forge pygeos
```
![Generate Heatmap using Datashader in Python and serve the heatmap tiles in OpenLayers map](Heatmap%20generation%20using%20Datashader%20in%20Python.gif)
## For tutorial post, click on following link<br/>
[Generate Heatmap using Datashader in Python and serve the heatmap tiles in OpenLayers map](https://spatial-dev.guru/2022/09/03/rasterize-vector-data-using-geopandas-and-geocube/)
