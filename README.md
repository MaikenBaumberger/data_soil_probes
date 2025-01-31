[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.13850543.svg)](https://doi.org/10.5281/zenodo.13850543)

# Soil temperature and soil moisture probe measurement data
This repository contains soil temperature and soil moisture time series data collected in the Fichtelgebirge Mountains between November 2021 and December 2022. Measurements were taken with 15 probes (Drill & Drop Probe RS232, Sentek Technologies, Australia), with a vertical resolution of 10 cm down to a depth of 90 cm or 120 cm. By shifting the probes on a weekly or monthly basis, the dataset includes measurements from 225 different locations. In addition, there were 2 permanent measurements.
Details on the soil probes and sampling design can be found in "High-resolution soil temperature and soil moisture patterns in space, depth, and time: an interpretable machine learning modeling approach", published in Geoderma.

The folder [probe_data](probe_data) contains all soil temperature and soil moisture measurements indicated by their probe ID. The file [probe_metadata.csv](probe_metadata.csv) provides all information about the measurements including their measurement period and location. The detailed definitions of the variables in the metadata and in the measurement files can be found in the file [explanation_variables.txt](explanation_variables.txt).

