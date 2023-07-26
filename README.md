# Runyan lab suite2p installation

1. Download the file: runyan_lab_suite2p.yml to a location on your computer
2. Open anaconda navigator and start base environment
3. cd to the location of the .yml file
4. conda env create --name runyan_lab_suite2p --file=runyan_lab_suite2p.yml

This will create a new anaconda environment with:

Suite2p version 0.10.3
Cellpose version 0.7.2
Rastermap version 0.1.3

+ several dependencies that are specific to these versions of suite2p, cellpose, and rastermap. 
