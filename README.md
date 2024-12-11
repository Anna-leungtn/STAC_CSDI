# STAC trial runs cataloging tifs (geotagged imagery)
### Process
* Download the raw data from the government 
* Unzip the raw data from a zipped file and decompose into .tif files 
* Turn the .tif into cloud optimised geotagged image files (cog.tif)
* Coordinate transformation from HK1980 to WGS84 
* Create a thumbnail imageries collection for those cog images (for quicklook usage)
* Upload the cog tif and thumbnail data into the server
* Create a STAC item for each of the tif data 
* Inside the item, define the asset with cog, thumbnail, quicklook and herf (link to the cog imagery)
* Create a STAC collection contains all the STAC item to build a collection 
* Create a STAC catalog to host the collection and associated items
* Regular maintain the STAC item for future updates
Data was collected from the CSDI Portal. 
