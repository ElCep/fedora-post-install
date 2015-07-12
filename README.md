Fedora Post Install Script
==========================

Original Author: Sam Hewitt
Modified : Etienne DELAY

License: GPLv3

Original source can be found [here](https://github.com/snwh/fedora-post-install).

##scientific stuff

I have modified the original script for add some geographical and scientific programs : 

 * [gdal](http://www.gdal.org/)
 * [geos](http://trac.osgeo.org/geos/)
 * [proj.4](https://trac.osgeo.org/proj/)
 * [grass](http://grass.osgeo.org/)
 * [Qgis](http://www.qgis.org/fr/site/)
 * [R](http://www.r-project.org/)
 * [Rstudio](https://www.rstudio.com/)
 * fresh [TeXLive](https://www.tug.org/texlive/) install

 By the way in the dev-tool section (4) it's now possible to install R packages for geographers ("rgdal","rgeos","proj4","maptools","plyr","ggplot2")


##Usage:

Download and run from the containing folder:

    bash fedora-post-install-script.sh


##About:

This project provides a simple set of bash scripts for simplifying the setup of a fresh system installation by installing your favourite applications, setting up system configurations, etc.

It is compatible with both 32 and 64 bit architectures 

Feel free to copy, improve and distribute.
