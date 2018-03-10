# PPI-Calculator
A ArcGIS tool for calculating the PPI vegetation index

A tool for ArcGIS written with python 2.7 in the ArcPy environment.
The tool computes the vegetation index PPI from various input data from specific known sensors such as
sentinel-2 or MODIS to name a few. Furthermore, manual data of the red and near-infrared band can be used as input
to calculate the PPI index.

The tool is delivered as a .tbx file with python code imbedded within it. The tool is provided in two iterations
where one being a simplified version without satellite platform support and the fully fledged version dubbed
"PPI_simple.tbx" and "PPI.tbx" respectively.

At the moment some satellite platforms are supported with their metadata as inputs for the parameters for the tool are:
- SPOT
- Sentinel-2

Parameters needed to calculate PPI can be done within the tool of itself, usage of platform metadata or manual input.
An example of this would be the solar zenith angle parameter which can be derived from Sentinel-2 metadata if Sentinel-2
data is used.

The equations are derived from the article "A physically based vegetation index for improved monitoring of plant
phenology" (2014) by Hongxiao Jin and Lars Eklundh at the university of Lund.

Some parameter values present in the equation needed to derive PPI are simplified so thusly the methodology/implementation
of the tool can be viewed in the "PPI_Paper.pdf" available for download.


This tool was created by Karl Adler, Simon Nåfält and Andreas Kroné as a part of a programming course at the
University of Lund. This software is free to use but please refer to Jin & Eklundh (2014) for a complete understanding
of the PPI vegetation index and its calculation. We take no credit of the theory, equations and derivations for the
calulation of the PPI vegetation index as this is merely a tool for its calculation in an ArcGIS environment.

If you have any questions or wishes of the tool dont hesitate to contact.
