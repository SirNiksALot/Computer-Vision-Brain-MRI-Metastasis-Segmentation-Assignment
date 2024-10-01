# Computer-Vision-Brain-MRI-Metastasis-Segmentation-Assignment

# Computer Vision: Brain MRI Metastasis Segmentation

This repository contains the implementation of computer vision techniques for brain MRI metastasis segmentation using two advanced architectures: Nested U-Net (U-Net++) and Attention U-Net. The goal of this project is to accurately segment brain metastases from MRI images, showcasing the performance of both models and providing a user-friendly web application for visualization.

## Table of Contents

- [Objective](#objective)
- [Dataset](#dataset)
- [Requirements](#requirements)
- [Installation](#installation)
- [Data Preprocessing](#data-preprocessing)
- [Model Implementation](#model-implementation)
- [Model Training and Evaluation](#model-training-and-evaluation)
- [Web Application Development](#web-application-development)
- [Usage](#usage)
- [Documentation](#documentation)
- [Challenges and Improvements](#challenges-and-improvements)
- [License](#license)

## Objective

Demonstrate proficiency in computer vision techniques by implementing and comparing Nested U-Net and Attention U-Net architectures for brain MRI metastasis segmentation, and developing a web application to showcase the model.

## Dataset

The dataset used in this project is the Brain MRI dataset, which can be downloaded from [this link](https://dicom5c.blob.core.windows.net/public/Data.zip). The dataset contains images and their corresponding segmentation masks. Images with missing masks and vice versa have been ignored.

### Dataset Structure
- `data/`
  - `images/`: Contains MRI images.
  - `masks/`: Contains corresponding segmentation masks.

## Requirements

To run the code in this repository, ensure you have the following Python packages installed:

- `torch`
- `torchvision`
- `segmentation-models-pytorch`
- `numpy`
- `opencv-python`
- `pydicom`
- `FastAPI`
- `uvicorn`
- `streamlit`
- `albumentations`
