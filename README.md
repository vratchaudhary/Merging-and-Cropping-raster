

##Download the DEM data. 
1. One source is USGS (https://earthexplorer.usgs.gov)

2. Open the Raster (tiff file) in QGIS window

3. If there are more than one file, you can merge them using Raster< Miscellaneous < Merge; where input file is the raster. Output file will be the new file in the desired location. To save space, remember to change your creation option to 'High Compression'


4. Now that merging is done, the new file created in step 3 can be cropped to the extent of desired shp file using clipper tool in QGIS. Raster< Extraction < Clipper will be tool where input file will be the new raster and 'mask' will be the shp file. 

5. The output file will be the desired raster. That easy!
