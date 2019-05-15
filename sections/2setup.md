[<<< Previous](1basic.md)  | [Next >>>](3layer1.md)  

# Setting Up

The first step is to [download and install QGIS here](https://www.qgis.org/en/site/forusers/download.html#).

Let’s imagine that there will be a flood in the East and Hudson Rivers, because of climate change and political neglect. We know that the flood will reach as far as 500 meters inland, and houses located anywhere under 15 meters above the sea level may be affected. Our task is to identify the blocks in a specific area of Manhattan that will be affected the most by this flood.

For this exercise, we will use:

1. A vector layer showing the census blocks in New York City;
2. A vector layer with the hydrography of New York City; and
3. A raster layer with the elevation of a specific quadrant in New York City.

We will get all three required layers from the [Cornell University Geospatial Information Repository (CUGIR) website](http://cugir.mannlib.cornell.edu/). If you want the real-world experience, go ahead and log into the CUGIR website and look for current datasets of New York City—specifically, the Census Blocks 2000 and the Hydrography (Census 2000). As for the raster image, look for the Digital Elevation Map (DEM) 10m raster of the Central Park quadrant in New York City. For convenience, you can download all three required layers in a single Zip file [here](https://github.com/dhsouthbend/mapping/blob/master/DHRI%20QGIS%20Files.zip). Decompress this Zip file in a familiar and easy-to-access folder. You should see three different folders that I labeled BLOCKS, HYDROGRAPHY and ELEVATION, each with their own files and folders inside (note that if you downloaded the files yourself from CUGIR they won’t have these names, but instead a generic CUGIR name and numbers).

[<<< Previous](1basic.md)  | [Next >>>](3layer1.md)  
