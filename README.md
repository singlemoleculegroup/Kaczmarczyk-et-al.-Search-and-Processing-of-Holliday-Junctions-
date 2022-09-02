# Kaczmarczyk-et-al.-Search-and-Processing-of-Holliday-Junctions-
scripts used to analyse the data in the manuscript by Kaczmarczyk et al. "Search and Processing of Holliday Junctions within Long DNA by Junction-Resolving Enzymes"

System requirements:
  - The analysis was performed on
  - operating system MacOS High Sierra, version 10.13.6
  - Python 3.9.4

The scripts are executed in Jupyter Notebook (Anaconda 4.10.1) using libraries:
  - numpy 1.20.3
  - matplotlib 3.4.2
  - statistics 
  - lumicks pylake 0.10.1 (https://lumicks-pylake.readthedocs.io/en/stable/install.html#)
  - scipy 1.6.3
  - peakutils 1.3.3
 
To install the software, download Anaconda: 
1. Go to the Anaconda website and download the Python 3.8 (or newer) installer.
2. Create a new environment for Pylake
3. Install additional libraries (scipy, peakutils through Anaconda desktop app or via Terminal)

Detailed instruction on how to install Anaconda and Pylake package is available here:
https://lumicks-pylake.readthedocs.io/en/latest/install.html#installation-instructions

The instalation process of Anaconda and necessary libraries requires ~15 minutes.

SCRIPTS TO ANALYSE IMAGES and FORCE (e.g. used to generate images for Figure 2)
To run the scripts, put a copy of the .ipynb Jupyter Notebook in the same folder as the .H5 file you wish to analyze. 
1. The script will automatically load the file. 
2. Subsequently, it will render a kymograph and the corresponding force measurement.
3. The kymograph can be then cropped and the image's brightness and contrast can be adjusted
4. Within the same script, it is possible to track 1D diffusion and measure the diffusion coefficient.


OUTPUTS:
-csv files with data 
- png images with kymographs
- raw TIFF file


For questions, contact akaczmarczyk88@gmail.com


