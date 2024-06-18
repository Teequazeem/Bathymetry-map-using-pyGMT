# Bathymetry-map-using-PyGMT
This code aims to generate a bathymetry map of the Gulf of Mexico.
To reuse this code, you want to ensure you modify the coordinates to your location of interest. 
Also, if you are interested in plotting the protraction areas on your plot, ensure you have the necessary files downloaded and modify the file path in the code accordingly. 

NOTE: PyGMT must be installed before importing. Check below for a simplified way of installing PyGMT on colab.

1. Install condacolab
!pip install -q condacolab
import condacolab
condacolab.install()

2. Install PyGMT
!mamba install pygmt

3. Import PyGMT
import pygmt


