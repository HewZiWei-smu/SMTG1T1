# SMTG1T1 - Ziwei & Theron

# Green Bangkok 2030 GIS Analysis

## Overview

This project analyzes Bangkok’s progress toward the three environmental targets set by the Green Bangkok 2030 Project. The analysis uses satellite imagery (Sentinel-2 L2A) from 2021 and 2025 to assess whether Bangkok is on track to meet its sustainability goals.

## Objectives

The Green Bangkok 2030 Project targets include:

1. **Increasing Green Spaces:** Achieving 10 square meters of green space per person.
2. **Improving Accessibility:** Ensuring public green spaces are accessible within 400 meters or a 5-minute walk for at least 50% of Bangkok’s total area.
3. **Expanding Tree Canopy Coverage:** Increasing urban tree canopy coverage to 30% of Bangkok’s total area.

## Methodology

- **Satellite Imagery Analysis:** Computation of Satellite - based raster imagery to classify vegetation.
- **GIS Techniques:** Buffer analysis, spatial clipping, raster-to-vector conversion, and change detection to assess goal achievement.
- **Visualization:** Interactive web maps created using QGIS2Web, embedded into a Quarto webpage.

## Timeline

Project conducted between March 9, 2025, and April 9, 2025.

## Running 

1. Clone the repository to your local server and use IDE of choice.
2. In the IDE terminal, run:

quarto preview

This command builds your website and starts a local server so you can see your changes in real time.

3. Should you wish to view the Interactive WebMap, please run the following commands to retrieve the map from Github's Large File Storage:

choco install git-lfs (Windows) / brew install git-lfs (Mac / Linux) 
git lfs install
git lfs pull

Should you run into any issues, kindly contact Ziwei or Theron. 
