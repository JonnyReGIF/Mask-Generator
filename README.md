## Welcome to the Mask Generator QGIS plug-in repository

The Plug-in is still under development, if you have feature requests or encounter any bugs pls open an issue.

Here a little plug-in is shared that simplifies training data generation for segmentation or classification models. 

## Installation instructions: 

- Download the complete main branch 
- Insert the .zip file to your QGIS installation ...\QGIS\QGIS3\profiles\default\python\plugins\
- Unpack and activate the extension in the QGIS extension manager
- Or just simply open the QGIS extension manager and choose the option "install from ZIP" and then enter the path to the downloaded file :) 


## Functionality:

- At first, specify an input directory. This directory should hold your previously tiled raster datasets.
  - All files that match the ".tif" file extension are then listed inside the list view widget.
- Next, specify an output directory, which is the directory where the digitalized masks will be saved.
- Now, one can load the first raster dataset using the "Load Raster" button. The first raster in the list will be loaded, and a corresponding vector layer is created.
- After digitization of the object of interest, one can save the changes using the "Save Vector Layer" button.
- Then, one can load the next raster tile, and again a new vector layer is created, ready for digitization.

<br></br>


![overview_final](https://github.com/user-attachments/assets/f68cb82e-4a44-4fdd-8cfb-73861a2dfbbf)
 






















