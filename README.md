Cartilage_thickness_from_CT
=======
Calculates cartilage thickness from a chosen location in CT image
-----------
Developed for Mach-1 measurements.
Original commit: Janne Mäkelä November / 2018

Click on the measurement location and measure
Calculates cartilage thickness from a chosen location in CT image.
Saves the coordinates where thicknesses have been calculated.

Currently converts the image stack so that the sample is observed from above (similarly as in Mach-1).
This is done inside load_dicoms (~line 169 ->) for dicoms or inside load_tifs (~line 201 ->) for tifs

added by Heta June / 2021:
show also the Mach-1 image under the CT image to see the exact locations
Mach-1 image has to be in the same orientation and same scale as the CT image ---->
for example, open both images in inkscape, rotate and resize the mapping image to
correspond with CT image (change the opacity of CT image to see better)
draw a rectancle around the ct image, hide the CT image, take a
screencap/save the image of the rectancle and the biomomentum grid image
-----------

**File list:**
  * Cartilage_thickness_from_CT.m - Analysis
  
-----------

**Preferable future commits:**
  * Better commenting
  * Flashier plots
  * _Fill_ _here_
  
------------