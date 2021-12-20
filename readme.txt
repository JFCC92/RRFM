This folder includes all the information needed to replicate the tests shown in this article.
 
The "Rapid Regional Flood Model" folder contains the "Flood.exe" file that runs the model.

The "Test #" folder contains the information needed to run each of the tests shown in the model:

-T#_DEM.grd. Digital elevation model.
-T#_MANNING. Manning's roughness coefficient grid.
-T#_IN. Input data for each test.
-T#_List_IN. List of input grids for each test if required.
-T#_List_MP. Identifiers "x" and "y" for each measurement point.

Results folder. Contains the results returned by the test:
-DEMWOF.grd. Corrected digital elevation model grid.
-T#_DEPTH.grd. Flood depth grid per cell in meters.
-T#_MAX_DEPTH. Maximum flood depth grid in meters.
-T#_WATER_LEVEL. Water level grid in meters.

IMG folder. This includes the image of the executable and the parameters to run each test.

