# Landslide Detection using Deep learning Algorithm

# Overview
This project implements a deep learning-based approach for landslide detection using Sentinel-2 multispectral data. It utilizes advanced segmentation models like U-Net, SegNet, and DeepLabV3+ to identify landslide-prone areas from satellite images. The pipeline includes preprocessing, model training, validation, and evaluation, integrating multiple features like RGB bands, NDVI, slope, and DEM for enhanced accuracy.

# Features

Preprocessing: Includes normalization, NDVI calculation, and feature extraction.
Deep Learning Models: Supports U-Net, SegNet, and DeepLabV3+ for segmentation tasks.
Metrics: Precision, recall, and F1 score for evaluating model performance.
Flexible Data Handling: Handles Sentinel-2 multispectral data with features like slope and DEM.

# Data Source
The dataset used in this project is available on Zenodo: https://zenodo.org/records/10463239



# Model Architecture

The repository includes implementations of:

U-Net: A popular encoder-decoder architecture for image segmentation.

SegNet: Known for its efficient upsampling and segmentation capabilities.

DeepLabV3+: Leverages atrous convolutions for capturing multi-scale context.
