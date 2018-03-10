# PPI-Calculator
A ArcGIS tool for calculating PPI

A tool for ArcGIS written with python 2.7 in the ArcPy environment.
The tool computes the vegetation index PPI from various input data from specific known sensors such as
sentinel-2 or MODIS to name a few. Furthermore, manual data of the red and near-infrared band can be used as input
to calculate the PPI index.

At the moment some satellite platforms are supported with their metadata as inputs for the parameters for the tool are:
- SPOT
- Sentinel-2

Parameters needed to calculate PPI can be done within the tool of itself, usage of platform metadata or manual input.
An example of this would be the solar zenith angle parameter which can be derived from Sentinel-2 metadata if Sentinel-2
data is used.

The equations are derived from the article "A physically based vegetation index for improved monitoring of plant
phenology" (2014) by Hongxiao Jin and Lars Eklundh at the university of Lund.

Some parameter values present in the equation needed to derive PPI are simplified and the methodology of the tool can be
viewed in the .pdf available for download.
