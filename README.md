# PlotFinder

The objective of this study is to segment plots in othromosaics using deep learning models and probably generate a shape files, that could be used in other GIS applications.

Workflow
- open rasters with geomatics information
- train deep learning models for plot identification
- establish a technique to slice the images and process through DL and put them togeather again
- get the masks and extract geomatic info on those
- convert masks to shapefile or polygons for GIS application