[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/pangeo-data/pangeo-docker-images/2021.09.30?urlpath=git-pull%3Frepo%3Dhttps%253A%252F%252Fgithub.com%252Flockecd%252Frces-final-project%26urlpath%3Dlab%252Ftree%252Frces-final-project%252F%26branch%3Dmain)

# Final Project

Caitlin Locke <br />
Research Computing in Earth Science <br />
Fall 2021 <br />

## Background

Knowledge of the bathymetry beneath floating ice shelves is important for future sea level rise and Antarctic Ice Sheet stability projections. Bathymetry, or seafloor topography, directs how ocean waters circulate underneath floating ice and controls ice-ocean interactions at the grounding line. In the coastal areas of Antarctica, satellite and ship-based bathymetry mapping is limited due to ice covered waters. As a result, bathymetry is not well known along the coastline of Antarctica. Inversion of airborne gravity data in these hard-to-access regions can provide reliable estimates of sub-ice shelf topography.


## Scientific Question

In the absence of a formal gravity data inversion, can a useful first look at sub-ice shelf bathymetry be provided by airborne gravity data in the coastal areas of Antarctica where ice covered waters limit ship and satellite mapping of bathymetry?

## Datasets

1. [IceBridge Sander AIRGrav L1B Geolocated Free Air Gravity Anomalies, Version 1](https://nsidc.org/data/IGGRV1B/versions/1)
1. [IceBridge LDEO Gravimeter Suite L1B Geolocated Free Air Gravity Anomalies, Version 1](https://nsidc.org/data/IGLGS1B/versions/1)
1. [IceBridge MCoRDS L2 Ice Thickness, Version 1](https://nsidc.org/data/IRMCR2/versions/1)
1. [MEaSUREs BedMachine Antarctica, Version 2](https://nsidc.org/data/NSIDC-0756/versions/2)
1. [MEaSUREs Antarctic Grounding Line from Differential Satellite Radar Interferometry, Version 2](https://nsidc.org/data/nsidc-0498)


## Summary of Analysis

I will estimate the bathymetry beneath the Venable Ice Shelf in Antarctica, in addition to the ice shelves associated with the De Haven, Frost, and Holmes Glaciers, using NASA's Operation IceBridge (OIB) airborne gravity data and the algorithm described in the supplementary materials of Hodgson et al. 2019. I will then compare the estimated bathymetry to the bed topography/bathymetry from MEaSUREs BedMachine Antarctica, Version 2 (BedMachine2). To test how effective this method is, I will calculate the water column thickness beneath the ice shelves using icebase data from OIB radar measurements and compare it to sub-ice shelf bathymetric pinning points identified in the MEaSUREs Antarctic Grounding Line from Differential Satellite Radar Interferometry (DInSAR), Version 2.

## References

Hodgson, D. A., Jordan, T. A., De Rydt, J., Fretwell, P. T., Seddon, S. A., Becker, D., Hogan, K. A., Smith, A. M., and Vaughan, D. G.: Past and future dynamics of the Brunt Ice Shelf from seabed bathymetry and ice shelf geometry, The Cryosphere, 13, 545–556, https://doi.org/10.5194/tc-13-545-2019, 2019.