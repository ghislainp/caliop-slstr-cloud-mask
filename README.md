# caliop-slstr-cloud-mask

This repository contains code and data to train and use ML algorithms to detect clouds in Sentinel 3 SLSTR images. The training dataset is composed of co-geolocalized data from CALIOP and SLSTR in Antarctica and Greenland. CALIOP is a lidar able to measure cloud properties profiles, and can be used to detect the presence of cloud with high precision. However it provides limited coverage. It is considered as the 'truth'. In constrast SLSTR is a multi-sprectal radiometer imager with bands adapted to cloud detection and wide daily coverage.

## Getting started

To clone this repository, [git lfs](https://git-lfs.github.com/) must be set up on your computer .

Explore the notebooks [train-random-forest.ipynb](https://github.com/ghislainp/caliop-slstr-cloud-mask/blob/main/notebooks/train-random-forest.ipynb) and [use-random-forest.ipynb](https://github.com/ghislainp/caliop-slstr-cloud-mask/blob/main/notebooks/use-random-forest.ipynb).

## Citation and Acknowledgment

This non-funded work provides open data and code freely. It is not published. Consider to contact the author if using these data or if more data are needed.

It is based on the original idea of a funded no-data-access project https://doi.org/10.1016/j.rse.2020.111999.

