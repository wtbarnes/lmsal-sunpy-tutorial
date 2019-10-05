# LMSAL SunPy Tutorial

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/wtbarnes/lmsal-sunpy-tutorial/master)

Materials for sunpy/aiapy tutorial at LMSAL on October 10, 2019. This tutorial will give an overview of how to do
analyze AIA data using sunpy and aiapy.

## Outline

* Querying AIA Data with Fido
  * Grab multiple images in time
  * Mention drms
  * Minimal example using drms to recombine headers and data
* Reading/loading AIA data
  * Just feed to Map!
  * Maybe show quick example of reading with astropy.io.fits 
* Anatomy of a Map
  * Data + metadata--show how to inspect both
  * Tour of attributes
  * What it does and does **not** do
* Image manipulation, coordinates, units
  * Submaps
  * Units
  * Coordinates
  * Converting between pixels and world coordinates 
  * Derotation
* Visualization
  * Example of plotting without maps (e.g. `imshow`)
  * Basics of plotting maps
  * Advanced examples ("an exercise for the reader")
    * Plotting multiple AIA images in a subplot with HPC ticks on llc, HGS ticks on urc
    * HMI full disk plus cutout with "zoom" (see Ch. 4 of thesis)
* Advanced Examples
  * Reprojection (see [this gist](https://gist.github.com/Cadair/5742d3f3f1d6e33c71510ede6426d6ed)) -- just show, don't dive into details
* An tour of aiapy
  * Correcting pointing keywords
  * Registration
  * Normalizing to exposure time
  * Correcting for image degradation
  * Response function calculations

## Brainstorming

* Would be nice to show how to stack images and create timeseries--maybe try out ndcube for this?
  * prep
  * derotate
  * stack
  * plot/extract timeseries
  * animate
  
## Resources
