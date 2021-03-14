# Arctic Basins

This repo contains shape files over Arctic region River Basins. The Basins are extracted from
the [PanArctic Digital Elevation Model (DEM)](https://doi.pangaea.de/10.1594/PANGAEA.779748) using 
a combination of GRASS GIS, GDAL,Python and QGIS as described in the blog 
[River basin delineation](https://nunataryuk.github.io). The python package [basin_extract](https://github.com/nunataryuk/basin_extract) 
is available on [GitHub.com](https://github.com). 

The basin data is available for different regions as ESRI shape files projected to EASE-grid 
north ([EPSG:6931](https://epsg.io/6931)). Version 01 (v01) available is extracted from DEM data 
resampled to 90m and nearest neighbour. The final vector map contains Basins larger than 50 square kilometers.
The xml files with each regional dataset contain the parameterisations for creating each Regional Basin file.

The mapping of Arctic Basins is part of the EU funded project [NUNATARYUK](https://nunataryuk.org). 
NUNATARYUK aims at determining the impacts of thawing coastal and subsea permafrost on the global climate, 
and will develop targeted and co-designed adaptation and mitigation strategies for the Arctic coastal population.
