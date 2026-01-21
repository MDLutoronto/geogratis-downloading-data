---
title: "Downloading Data from GeoGratis"
layout: "home"
description: ""
permalink: "/"  #! Remove this if not the homepage
---

# Downloading Data from GeoGratis

*National Resources Canada (NRCAN)* produced a portal called GeoGratis for allowing access to, and downloads of, their high\-quality, free, and publicly available maps and geospatial data. This tutorial guides you in navigating their Product Index to find data on a specific location, and it is easily adaptable for other locations or desired data products.

To locate and download data on an area of interest, using Toronto, Ontario as an example:

1. **Begin by going to the GeoGratis homepage: <http://geogratis.gc.ca> and select your language of choice.** 
![Select language]({{ '/assets/images/Geogratis_Tutorial_001.png' | relative_url }})
2. **Under Geospatial Applications and Tools, click on Geospatial Product Index – HTML.  
![Highlighting location of Geospatial Product Index in HTML]({{ '/assets/images/Geogratis_Tutorial_002.png' | relative_url }})**
3. The Geogratis tool has an interactive map on the right and menus nested within tabs on the left.  
![Highlighting location of tabs and maps on Interface ]({{ '/assets/images/Geogratis_Tutorial_003.png' | relative_url }})
4. There are several kinds of maps and geospatial datasets available through this portal. **Begin by clicking on the Themes tab.**
5. Each of the four menus, \- Imagery, Raster, Vector, and Elevation, \- contain multiple kinds of downloadable datasets.  
**Imagery** contains orthoimagery (corrected aerial photographs) at various scales for all of Canada.  
**Raster** contains topographic maps, which show physical features such as roads and rivers.  
**Vector** contains a variety of features, both physical and cultural, which can be downloaded as file geodatabases or shapefiles.  
**Elevation** contains Digital Elevation Models (DEM) and Digital Surface Models (DSM) for all of Canada.
6. For the purposes of this tutorial, let’s locate the map sheet from the [*National Topographic System (NTS)*](https://www-nrcan-gc-ca.myaccess.library.utoronto.ca/earth-sciences/geography/topographic-information/maps/national-topographic-system-maps/9767) for downtown Toronto. **Click on Raster.  
![Highlighting Themes tab and Raster sub tab]({{ '/assets/images/Geogratis_Tutorial_004.png' | relative_url }})**
7. **Then, click on “Digital Topographic Raster Maps \- 1:50 000”.  
![Highlighting Digital Topographic Raster Map 1 to 50 thousand scale]({{ '/assets/images/Geogratis_Tutorial_005.png' | relative_url }})**
8. You will see an index appear over Canada. Each tile within that index corresponds to a different NTS map sheet. **Use the interactive map to zoom in on downtown Toronto, Ontario.** As you zoom in, you will see a series of grids appear over Canada.
9. First, a series of numbers will appear; Toronto is located in grid "030".
10. As you continue zooming in, Toronto will be sector "M" of section "030".
11. Going further, zoom in on subsection "11".
12. The grid location for the map sheet for downtown Toronto is 030M11\. **Click on the tile labelled 030M11\.  
![Grid location for downtown Toronto]({{ '/assets/images/Geogratis_Tutorial_006.png' | relative_url }})**
13. Once you click on a tile, the side menu changes to the “Preview and download” tab. There is a thumbnail of the map sheet in question, with a download link. **Click on “Download link / Lien de téléchargement.”  
![Preview and download link location]({{ '/assets/images/Geogratis_Tutorial_007.png' | relative_url }})**
14. You will be presented with a few download options. Please however your mouse over each file. Near the bottom\-left side your screen, it should reveal the full file name in the URL preview. Please click and download the from the link ending in **geotiff.zip.  
![Three download options]({{ '/assets/images/Geogratis_Tutorial_008.png' | relative_url }}) ![URL showing link ending in geotiff]({{ '/assets/images/Geogratis_Tutorial_009.png' | relative_url }})**

Once it has downloaded, you can unzip it and bring it into a GIS program like ArcGIS Pro or QGIS. You can also modify the above instructions to download DEMs, orthoimagery, or vector files from NRCAN.

Technique: [Searching for maps and data](/technique/searching-maps-and-data), [Extracting data](/technique/extracting-data) \| Tools: [GeoGratis](/tools/geogratis-0) \| Data Format: [DEM](/data-format-tutorials/dem), [Raster](/data-format/raster)**Date Created:** 2021\-01\-15**Updated:** 2022\-12\-13
