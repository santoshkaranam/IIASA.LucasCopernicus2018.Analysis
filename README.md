# LUCAS Copernicus Polygons analysis for Flanders (Belgium)

## Problem: When comparing LUCAS Copernicus 2018 polygons with Belgium Flanders LPIS 2018 we noticed some polygons crossed parcel boundaries and sometimes roads.
How we analyzed the data: 
1.	Extracted polygons that cross parcel boundaries along with their land cover classes (values).
2.	Extracted polygons that overlap roads.
3.	Determined the amount of such polygons and compare against polygons which are entirely within parcel boundaries .
Dataset for roads in Belgium is taken from OSM. For simplicity, the latest OSM map is used. OSM roads for Belgium is downloaded from http://download.geofabrik.de/europe/belgium.html

## Results
Total LUCAS Copernicus polygons in Flanders-	261	(100%)

Polygons crossing LPIS parcels-	52	(20%)

Polygons crossing OSM roads-	30	(11%)

Examples of polygons crossing roads(from OSM, shown on google maps as base imagery): LucasCrossesRoads.geojson

Polygons crossing field boundaries of 2018 LPIS (green=LPIS, Red= LUCAS Copernicus): LucasCrossesParcels.geojson

### Note: 
Since polygons are small, you may have to zoom into the Flanders Region in Belgium. If required, the geojson can be downloaded and checked in QGIS.
