# Irie_Brown_UV_Protection_of_Cell_free_Reactions_2025
## **Code for Irie and Brown et. al. “UV-Resistant Cell-free Reactions with Synthetic Melanin Additives”**

This repo contains python code and data files for analysis used in Irie and Brown et. al. “UV-Resistant Cell-free Reactions with Synthetic Melanin Additives”
1.	`Python_Code_Figures.ipynb` contains code for generating all of the heatmaps contained in the paper figures and supplementary information. 
2.	`DLS.ipynb` contains code for analyzing the DLS data for nanoparticle characterization 

## **Downloading Files**
Files can be downloaded manually or obtained by:
   
    git clone https://github.com/LucksLab/Irie_Brown_UV_Protection_of_Cell_free_Reactions_2025.git

## **System Requirements**
The python packages required for a Python 3 Jupyter Notebooks are as follows

    import pandas as pd
    import numpy as np
    import matplotlib.pyplot as plt
    import seaborn as sns
    import glob

## **Code Usage**

### *Figure Data*
For `Python_Code_Figures.ipynb`

Excel files `DNAConcMap.xlsx`,`DNAConcMap_RAW.xlsx`,`J23119UVMap.xlsx` ,`J23119UVMap_RAW.xlsx` ,`LyoMap.xlsx` ,`LyoMap_RAW.xlsx`,`T7_UVMap.xlsx`  ,`T7UVMap_RAW.xlsx`,`T7_J23119_Ctrl_Particle_Map.xlsx`,`T7_J23119_Ctrl_Particle_Map_RAW.xlsx`, and`T7_J23119_Ctrl_Particle_Map.xlsx`      are used for `Python_Code_Figures.ipynb` and should be downloaded. 

Change the path found in the Jupyter notebook to the path of xlsx files

Running this notebook should generate output files SVG output files for each figure 
For `DLS.ipynb`

Download the file `Particles_Compiled_DLS.csv` and change the path if necessary. Running this will result in a saved image files of nanoparticle DLS data, DLS_NPs.png

