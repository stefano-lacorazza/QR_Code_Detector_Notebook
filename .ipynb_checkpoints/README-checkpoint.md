
# QR Code Detection, Cropping, and Decoding using Machine Learning

This repository contains code and resources for a machine learning model that detects, crops, and decodes QR codes from images using a Jupyter Notebook.

## Overview

QR (Quick Response) codes are two-dimensional barcodes that store various types of information. This project focuses on creating a machine learning model to automatically detect QR codes within images, crop them for better isolation, and decode the information contained in the QR codes.

## Repository Structure

The repository is organized as follows:

- `datasets/`: Main dataset used to train the model, with images separated into test, train, and validate folders.
- `datasets 0/`: Previous dataset used to train the model, with images separated into test, train, and validate folders.
- `Images/`: Pre-processed dataset of images with and without QR codes.
- `models/`: Previous models.
- `QR-codes/`: Folder to save cropped QR codes from images.
- `runs/`: Folder containing all previous machine learning models, with the final one located in `train 12/`.
- `QR-detector.ipynb`: Jupyter Notebook containing the code for the project.
- `IMG_20230820_100924_960.jpg`: Image used for manual testing of the model.

## Getting Started

1. Clone the repository to your local machine:

```bash
git clone https://github.com/your-username/qr-code-detection.git
cd qr-code-detection
