# AR Catalog Tutorial

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jbbutler/AR-Catalog-Tutorial/HEAD?labpath=catalog_tutorial.ipynb)

Welcome! This repository contains a Jupyter notebook showcasing the Antarctic atmospheric river catalog from the AGU24 poster "Quantifying the association between Antarctic atmospheric river characteristics and their impacts using extreme-value statistics" ([link to abstract](https://agu.confex.com/agu/agu24/meetingapp.cgi/Paper/1653296)). Feel free to play around and email me if you have any questions at butlerj@berkeley.edu!

## Contents
+ `Butler_AGU24_poster.pdf`: the poster in question
+ `catalog_tutorial.ipynb`: the tutorial notebook that interactively walks you through the catalog and shows you what it can be used for!
+ `environment.yml`: a file that contains the conda environment necessary to run the tutorial
+ `catalog_display.py`: a python file with functions to display catalog in tutorial
+ `MERRA2_gridarea.nc`: a mapping from pixel to area occupied, used in the tutorial
+ `2022_storm_df.h5`: one year of storms from the event-based catalog

## Notebook Access

To access the notebook, you can click the above 'launch binder' button! This will take you to an interactive, online Jupyter notebook with all packages pre-installed. *Note: it may take a few moments for it to load..*

Furthermore, if you'd like to play around on your own local Jupyter server, feel free to clone the repository if you like, ensuring that all of the above files are in the home folder. Then, make a conda environment out of the provided .yml file by calling `conda env create --name <your env name> --file=environment.yml`, activate it with `conda activate <your env name>`, and then call `python -m ipykernel install --user --name=<your env name>` so that you can see this environment as an available kernel in Jupyter. After this, you should be set!
