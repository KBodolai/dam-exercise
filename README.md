# dam-exercise

> Exercise demonstrating stac + xarray for remote sensing analysis.

This is supposed to be a simple exercise leveraging STAC items in the planetary computer and xarray to extract information about the Lower Sesan 2 dam in Cambodia.

## Setup

Setup should be relatively simple, and everything has been run and tested with a machine with 4 cores and 16GB RAM. You'll need to clone this repository:

```sh
git clone https://github.com/KBodolai/dam-exercise
cd dam-exercise
```

We recommend using conda for managing dependencies:

```sh
conda create -n <environment-name> python=3.12
conda install -c conda-forge jupyter gdal
pip install -r requirements.txt
```
