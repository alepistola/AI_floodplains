# AI Floodplains
Code repository for the paper "AI-ming backwards: Vanishing archaeological landscapes in Mesopotamia and automatic detection of sites on CORONA imagery" submitted to PLOS ONE

This repository contains the code described in the paper "AI-ming backwards: Vanishing archaeological landscapes in Mesopotamia and automatic detection of sites on CORONA imagery " by A.Pistola, V.Orrù, N.Marchetti and M.Roccetti.

The Python script stampa_imm_qgis is a script to be used inside QGIS. It contains functions to save the input images and target masks for the segmentation models starting from the shapefiles included in the zip folder and using a Bing basemaps and Corona basemaps (https://corona.cast.uark.edu/atlas). Notice that when saving the input images all layers other than the basemap should be set to invisible. On the other hand when saving masks site shapes should be the only visible layer and should be styled as all black filled polygons (a QGIS style is included)

The iPython notebook contains all the code needed to train and evaluate models.

The remaining contents are support .csv and .json files that made deveopment easier.

Precomputed datasets and model checkpoints are available upon request due to the file size. For access to the checkpoints and related work from the previous published research, please refer to the following repository: [tell_segmentation](https://github.com/mister-magpie/tell_segmentation).
