# Brain Tumor Classification using Convolutional Neural Networks

This project uses a convolutional neural network (CNN) to classify MRI brain scans into two categories: those that contain brain tumors and those that do not. The model is trained on a dataset of labeled [brain MRI images from a Kaggle dataset](https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection/data).


## Features

- Fetch images from specified URLs.
- Data preprocessing includes image resizing and normalization.
- Data Augmentation
- Split the image data into training and testing datasets.
- Built CNN Model
- Binary classification to detect the presence or absence of brain tumors.
- Evaluation of model performance using accuracy and loss.

## Requirements

Before running this project, you will need the following:
- Python 3.8 or later
- pip (Python package installer)

- tensorflow: For building and training the neural network models.
- Pillow: For image manipulation tasks.
- numpy: For numerical operations.
- matplotlib: For plotting graphs.
- seaborn: For enhanced data visualization.
- requests: For HTTP requests to retrieve images.
- sklearn: For machine learning tools like train-test splitting and metrics calculation.

You can install these dependencies via pip:
```
!pip install numpy tensorflow opencv-python matplotlib requests Pillow
```

## Installation

To set up the project environment:
1. Clone the repository:
```
   git clone https://github.com/yourusername/brain-tumor-classification.git
   cd brain-tumor-classification
```



## Contributers
- Maria Estrada - Ariamestra
- Mauren Vasquez - marsvx
