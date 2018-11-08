# 2018_05_light_pollution_linear_vegetation_change_in_time

authors: Peter Pastorek, Martin Galis, Jozef Novacek

## Summary
Light pollution modeling of selected region based on EU DEM (Copernicus Land service) and selected OSM building types. Modeling was based on multisource Viewshed analysis with light source height and view distance defined.

## Motivation
Satelite imagery on light pollution does not exist in Copernicus programme. This exercise explores possibilities of light pollution modeling based on DEM model and sources of lights based on viewshed visibility analysis. 

## Target user groups
- Nature protection (inpact of light polution on small animals, definiton of biocenters) 
- Tourism (sky observation, wilderness hiking)
- Public sector

## Results
 - Presentation:   https://github.com/danubehack/2018_05_light_polution_linear_vegetation_change_in_time/blob/master/06_Light_pollution_modeling__Urban_Vegetation_change.odp?raw=true

- Input data:
    DEM (Geo Tiff)
https://github.com/danubehack/2018_05_light_polution_linear_vegetation_change_in_time/blob/master/viewshed_dtm.tif
https://github.com/danubehack/2018_05_light_polution_linear_vegetation_change_in_time/blob/master/viewshed_dtm.tif.aux.xml

 - Viewpoints derived from OSM buildings(ESRI SHP)
https://github.com/danubehack/2018_05_light_polution_linear_vegetation_change_in_time/blob/master/viewpoints_final_crop_centroids.shx
https://github.com/danubehack/2018_05_light_polution_linear_vegetation_change_in_time/blob/master/viewpoints_final_crop_centroids.shp
https://github.com/danubehack/2018_05_light_polution_linear_vegetation_change_in_time/blob/master/viewpoints_final_crop_centroids.qpj
https://github.com/danubehack/2018_05_light_polution_linear_vegetation_change_in_time/blob/master/viewpoints_final_crop_centroids.prj
https://github.com/danubehack/2018_05_light_polution_linear_vegetation_change_in_time/blob/master/viewpoints_final_crop_centroids.dbf
 
 - Output data:
    Processed light pollution
https://github.com/danubehack/2018_05_light_polution_linear_vegetation_change_in_time/blob/master/final_viewshed.tif
https://github.com/danubehack/2018_05_light_polution_linear_vegetation_change_in_time/blob/master/final_viewshed.tif.aux.xml 

 - Working script(Python, QGIS experimental script):
https://github.com/danubehack/2018_05_light_polution_linear_vegetation_change_in_time/blob/master/ViewshedAnalysis-0.6.4_scritp.zip

- Presentation: https://github.com/danubehack/2018_05_light_polution_linear_vegetation_change_in_time/blob/master/06_Light_pollution_modeling__Urban_Vegetation_change.odp
- Video: https://youtu.be/tSoGZiaiOZY
