# 18CSE399J-Environmental-Hydrology-for-Data-Science
# Problem statement
*There are a lot of water bodies and reservoirs in the world which are depreciating at a very fast pace and certain steps need to be taken to ensure these levels are made stable.*

# Objective
*Using ML and Satellite images dataset we will be predicting if a water body will be receding in the future or not.*
# Dataset Used
_This data set provides the water quality classifications of New York State's lakes, rivers, streams and ponds, collectively referred to as waterbodies. All water bodies in the state are provided a water quality classification based on existing, or expected best usage, of each waterbody or waterbody segment. Under New York State's Environmental Conservation Law (ECL)_
[**Sample Dataset**](https://www.kaggle.com/new-york-state/nys-waterbody-classifications?select=waterbody-classifications.csv)



# Architecture or Model
_With the use of machine learning tools we can preprocess images and combine them with standard QGIS tools to delineate objects in a much efficient way._
 #### Required Packages
 **#python and matplotlib libraries**
 <br/>
import numpy as np
<br/>
import matplotlib.pyplot as plt

**#geospatial libraries**
<br/>
import rasterio

**#machine learning libraries**
<br/>
#!pip install scikit-image
<br/>
from skimage import feature

# Predicted Output
It shows a mixed procedure that detects edges with Python and Scikit Image , traces paths with QGIS and the Trace Raster plugin and finally gets the lake extension as a Shapefile.

# References
[LINK 1](https://hatarilabs.com/ih-en/delineate-water-bodies-lakes-from-landsat-8-using-machine-learning-with-python-and-qgis-tutorial)
<br/>
[LINK 2](https://www.hindawi.com/journals/abb/2020/6659314/#abstract)

