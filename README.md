# Darling River Shape Files

This is a repo for shape files the Darling River as well as any tributaries and 
distributaries of the Darling river above Wentworth.

## Project Details

The project is set up as an [QGIS project](https://www.qgis.org/en/site/) project, however
you can use any GIS application to edit the shapefiles.

### Directory layout

* data/spatial/vector
  This contains the shapefiles

* data/spatial/raster
  This contains any photos etc

* web
  Primarily for simplified KML exports of any of the rivers.

### Shapefiles

CRS: EPSG:4326 - WGS 84 - Geographic
Project Units: m
Fields
* name: Name of the river (string 80)
* length: Length of the vector in km (decimal 10/3) 
  calculated by $length / 1000
  

### Simplify

1 m = 0.00001
5 m = 0.00005
10 m = 0.0001

## River Status

Balonne - Low quality
Barwon - Good, shortcuts to add
Bomii - Stub
Condamine - Low quality
Culgoa - Low quality
Darling - Good, shortcuts to add
Dogwood - Low qaulity
Dumaresq - Stub
Great Darling Anabranch - Good quality, update after trip
Macintyre - Low quality
Macquarie - Low quality
Murray - Placeholder, see the Murray project for river data
Paroo - Low quality
Weir - Stub
Warrego - Low quality
  
### License

This work is licensed under the Creative Commons Attribution 4.0 International License. To
view a copy of this license, visit http://creativecommons.org/licenses/by/4.0/ or send a 
letter to Creative Commons, PO Box 1866, Mountain View, CA 94042, USA.

