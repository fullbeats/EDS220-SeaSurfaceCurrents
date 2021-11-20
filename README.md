# EDS 220 - Remote Sensing - Homework 3
## Visualizing HFR Surface Current data for Huntington Beach Oil Spill 2021
### Elmera Azadpour, Ian Brunjes, Phillip Puettmann, Quin Smith

<img width="1226" alt="HF Radar" src="https://user-images.githubusercontent.com/69014273/142695083-f95f439d-c9e1-4230-9120-de5bae4562b9.png">

## What is this made for?
This notebook was composed for the "Remote Sensing" class of "Environmental Data Science" (EDS 220) at the University of California Santa Barbara in Fall 2021. 
It provides an introduction to using high frequency radar (HFR) data from the Integrated Ocean Observing System network to derive surface current velocity and direction in the Huntington Beach area during the recent oil spill. 

## What data do you use?
Here, we utilize 6 km resolution (hourly) HFR data of surface currents and oil blob movements over time with data provided by the Coastal Observing Research and Development Center at Scripps Institution of Oceanography, UCSD and the Environmental Response Management Application (ERMA), respectively.

## What language / packages do you use?
The Python code is wrapped in a Jupyter notebook for convenient explanations and code aside. Data is mainly wrangled using xarray and geopandas. Plotting and animations are done by matplotlib and contextily.

## How to run?
The easiest way of running the data in a clean Jupyter Notebook environment using the provided Binder instance. Just click the button below and it starts a new Binder instance for you. In case you want to use your own environment, you are free to do that as well!

_IMPORTANT:_ In order to get the animations right, you must make sure to run the Notebook within a Jupyter*Notebook* instead of a Jupyter*Lab* instance. You can do so by replacing the URL suffix */lab/tree/HW3_rs_crew.ipynbto */notebooks/HW3_rs_crew.ipynb after the Jupyter Instance has loaded completely.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fullbeats/EDS220-SeaSurfaceCurrents/HEAD)
↑↑↑↑↑↑↑↑↑↑↑↑↑↑↑
click the binder icon above to begin. A remote python session will launch in your browser with the tutorial Be patient, sometimes it takes a while for the session to initalize the first few times.

## Troubleshootng
Are you getting a weird "Javascript Error: IPython is not defined" error message? That is probably because your notebook is run within a JupyterLab instance instead of a JupyerNotebook instance. See hints in the section above to get rid of this problem!

### Questions?
If you have any issues or questions, please feel free to contact any of us via the contact information given in the GitHub profiles.