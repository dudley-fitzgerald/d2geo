# d2geo
Framework for computing seismic attributes with Python

## Get started

In this example, we demonstrate how to use *d2geo* to produce seismic attributes in the inlines, crosslines, timeslices, and the whole volume of Dutch F3 seismic data. 

Read the SEGY file. There are Python libraries that can be used to read SEGY, for instance [`segyio`](https://github.com/equinor/segyio). 

we need to have a data cube (Numpy or HDF5) for the input. 
