# Dark2Light: A GAN-based Approach for Low-Light Image Enhancement

This repository contains the implementation of a Generative Adversarial Network (GAN) for low-light image enhancement. The project aims to improve the quality of low-light images by generating well-lit counterparts using deep learning techniques.

## Overview

The Dark2Light model is built using PyTorch and consists of two main components: a generator network and a discriminator network. The generator network takes a low-light image as input and generates an enhanced, well-lit version of the image. The discriminator network acts as a critic, distinguishing between real well-lit images and generated images, providing feedback to the generator during training.

## Dataset

The project uses the LoL (Low-Light Image Enhancement) dataset, which consists of pairs of low-light and well-lit images. The dataset is automatically downloaded and preprocessed during the training process.

## Requirements

- Python 3.x
- PyTorch
- NumPy
- Matplotlib
- Pillow
- scikit-image

## Usage

1. Clone the repository: git clone https://github.com/Arjunn786/Dark2Light.git

2. Install the required packages: pip install -r requirements.txt
