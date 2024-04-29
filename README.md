# Brain Tumor Classification using Convolutional Neural Networks

This project uses a convolutional neural network (CNN) to classify MRI brain scans into two categories: those that contain brain tumors and those that do not. The model is trained on a dataset of labeled [brain MRI images from a Kaggle dataset](https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection/data).


## Features

- Data preprocessing includes image resizing and normalization.
- Model built using TensorFlow and Keras.
- Binary classification to detect the presence or absence of brain tumors.
- Evaluation of model performance using accuracy and loss.

## Prerequisites

Before running this project, you will need the following:
- Python 3.8 or later
- pip (Python package installer)

## Install the required packages
```
!pip install numpy tensorflow opencv-python matplotlib
!pip install numpy requests Pillow
```

## Installation

To set up the project environment:
1. Clone the repository:
```
   git clone https://github.com/yourusername/brain-tumor-classification.git
   cd brain-tumor-classification
