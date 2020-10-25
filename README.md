# d2geo
Framework for computing seismic attributes with Python

## Get started

In this example, we demonstrate how to use *d2geo* to produce seismic attributes in the inlines, crosslines, timeslices, and the whole volume of Dutch F3 seismic data. 

Read the SEGY file. There are Python libraries that can be used to read SEGY, for instance [`segyio`](https://github.com/equinor/segyio). 

```
Inline range from 100 to 750
Crossline range from 300 to 1250
TWT from 4.0 to 1848.0
Sample rate: 4.0 ms
The 99th percentile is 6517; the max amplitude is 32767
```

we need to have a data cube (Numpy or HDF5) for the input. 
