[![DOI](https://zenodo.org/badge/833603533.svg)](https://doi.org/10.5281/zenodo.14019716)

# Neutral network implementation to raman data 

## Overview

This repository is part of article - Chemistry of Street Art: Neural Network for the Spectral Analysis of Berlin Wall Colors. 

This repository contains research on the correlation between peak intensity and compound percentage in Raman spectra, focusing on the use of deep learning to quantify pigment mixtures in commercial acrylic products. Using a handheld Raman spectrometer (BRAVO by Bruker), the study demonstrates the effectiveness of a Convolutional Neural Network (CNN) in analyzing spectral data to predict the ratios of coloring compounds. Calibration and training were conducted with reference materials created by diluting Schmincke brand acrylic paints, commonly used by street artists. This research represents the first application of Raman spectroscopy for calibrating dye dilution in commercial pigment mixtures, offering a novel analytical approach for quantifying pigments in street art materials and deepening insights into artists' techniques and materials.

## Repository structure

├── data/
│   └── blue
|       └────PB-conc-x_test-y.csv (files)
|    └── csv-clean
|    └── csv-clean-renamed
|    └── dpt
|    └──green
|       └────GR-conc-x_test-y.csv (files)
|    └──mockup-files 
|    └──raw
|    └──red
|       └────PR-conc-x_test-y.csv (files)
|    └──yellow 
|       └────PY74-conc-x_test-y.csv (files)
├── utils
|    └──convert-dpt-to-csv.ipynb
├── SAPNet.ipynb
├── requirements.txt
└── README.md