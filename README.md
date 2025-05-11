# NASA STV Tools

## Overview

This repository provides analytical tools and visualizations to support NASA's Surface Topography and Vegetation (STV) program. These tools are designed to evaluate the accuracy of surface trend measurements using remote sensing data as a function of observation frequency, measurement uncertainty, and spatial coverage. They are particularly relevant for mission planning and data interpretation activities within the STV framework.

## Contents

### 1. Trend Uncertainty Estimation
This section evaluates how the standard error of estimated surface elevation trends varies as a function of:
- Number of acquisitions per year
- Length of observation period (1 year vs. 3 years)
- Per-measurement vertical accuracy

### 2. Event Detection Probability (ICESat-2 Geometry)
This component estimates the probability of missing deformation events using fixed-beam spacing geometry typical of satellite missions such as ICESat-2.

## Usage
All plots and calculations are contained in a single Jupyter Notebook provided in this repository.

## Requirements
- Python 3.7+
- NumPy
- Matplotlib

## Citation
If you use this toolset in your research or reporting, please cite this repository as:
> NASA STV Tools (2024). Tools for Trend Estimation and Event Detection in Surface Topography Analysis. https://github.com/yourusername/nasa-stv-tools
