# Software Development Final Project
Final project for the course Software Development @[PLUS](https://www.plus.ac.at/)

# Identifying and upscaling vegetation endmembers from UAV imagery to estimate vegetation diversity at larger scale applications
Henrike Dierkes, Edgar Manrique, Kiarash Pooladsaz

## Aim
- Identify the proportion of different vegetation species within a pixel by upscaling UAV derived vegetation endmembers, using Linear Spectral Mixture Analysis (LSMA)
    - Automatically extract endmember spectra from UAV images using stratified random sampling and an unsupervised clustering algorithm to differentiate vegetation endmembers.
    - Apply LSMA to estimate vegetation diversity.
    - Make an interactive web application using streamlit.io to visualize the results and modify some parameters interactively.

![UAV derived vegetation endmembers](img/SoftDev-01.png)

## Expected Outcomes
- Combine UAV and Satellite imagery for LSMA.
    - Algorithms to identify endmembers in UAV imagery.
    - Algorithms to upscale UAV derived endmembers to coarser resolution satellite imagery.
- Standardized workflow for LSMA.
- Streamlit application.

## Data
- Sentinel 2 Level 2A cloud free mosaic (10m pixel size). 
- UAV imagery (~2cm pixel size). 

## Responsibilities
- Conceptualization of the idea (Henrike, Edgar, Kiarash).
- Endmembers extraction from UAV imagery (Henrike & Edgar).
- LSMA Analysis (Henrike & Kiarash).
- Web application (Edgar & Kiarash).

## Due date
- 15th July 2022

## Expected time effort
- Kiarash: 30h
- Edgar: 30h
- Henrike: 30h 
