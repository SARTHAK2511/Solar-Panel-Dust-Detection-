# Solar Panel Dust Detection

This repository contains the Jupyter Notebook file (`solar_panel_dust_detection.ipynb`) used for training a custom VGG16 model for dust detection on solar panels using TensorFlow and Keras.

## Overview

In this project, we utilize a custom VGG16 convolutional neural network to detect dust on solar panels. The model is trained on a dataset of images containing both clean and dusty solar panels. Through this, we aim to develop a robust system for automated detection of dust accumulation on solar panels, enabling timely cleaning and maintenance.

## Files

- `solar_panel_dust_detection.ipynb`: Jupyter Notebook containing the code for training the custom VGG16 model.
- `trained_dust_detection_model.h5`: The trained model saved in HDF5 format.

## Usage

1. Clone this repository:

    ```bash
    git clone https://github.com/your-username/solar-panel-dust-detection.git
    ```

2. Navigate to the repository directory:

    ```bash
    cd solar-panel-dust-detection
    ```

3. Open and run the Jupyter Notebook `solar_panel_dust_detection.ipynb` to train your custom VGG16 model for dust detection on solar panels.

## Dataset

The dataset used for training consists of labeled images of solar panels, categorized into clean and dusty instances. It's essential to ensure the dataset adequately represents the variability of dust accumulation scenarios encountered in real-world conditions.

## Requirements

- TensorFlow
- Keras
- Jupyter Notebook

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
