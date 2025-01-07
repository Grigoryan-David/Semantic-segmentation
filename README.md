# Semantic Segmentation Project

This project implements semantic segmentation using a U-Net model from the `segmentation_models_pytorch` library. The model is trained and evaluated on the CamVid dataset.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Dependencies](#dependencies)
- [Usage](#usage)
- [Acknowledgments](#acknowledgments)

## Overview

The project focuses on segmenting road scene images using the U-Net architecture. It leverages the `segmentation_models_pytorch` library for efficient model implementation and training.

## Dataset

The CamVid dataset is used for this project. It contains road scene images with pixel-level annotations. The dataset is structured as follows:

```
CamVid/
  train/
    images/
    labels/
  val/
    images/
    labels/
  test/
    images/
    labels/
```
Ensure the dataset is downloaded and organized in this format.

## Model Architecture

The U-Net model is utilized for its strong performance in segmentation tasks. It comprises an encoder-decoder structure with skip connections, enabling precise localization and segmentation.

## Dependencies

This project requires the following Python packages:
- Python 3.9+
- PyTorch
- segmentation-models-pytorch
- torchvision
- matplotlib
- pandas
- numpy
- torchmetrics
- tqdm
- TensorBoard

Install the dependencies using:
```
pip install -r requirements.txt
```

## Usage

Clone the repository:
```
git clone https://github.com/Grigoryan-David/Semantic-segmentation
```

## Acknowledgments

- [segmentation_models_pytorch](https://github.com/qubvel/segmentation_models.pytorch): For providing the U-Net model.
- [Camvid Dataset](https://www.kaggle.com/datasets/carlolepelaars/camvid): For hosting the CamVid dataset
