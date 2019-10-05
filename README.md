# LMSAL SunPy Tutorial

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/wtbarnes/lmsal-sunpy-tutorial/master)

Materials for sunpy/aiapy tutorial at LMSAL on October 10, 2019. This tutorial will give an overview of how to do
analyze AIA data using sunpy and aiapy.

## Outline

* Querying AIA Data with Fido
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
* Visualization
  * Example of plotting without maps (e.g. `imshow`)
  * Basics of plotting maps
  * Advanced examples ("an exercise for the reader")
    * Plotting multiple AIA images in a subplot with HPC ticks on llc, HGS ticks on urc
    * HMI full disk plus cutout with "zoom" (see Ch. 4 of thesis)
* An intro to aiapy

## Resources
