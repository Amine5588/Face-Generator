# Face-Generator
Using GAN to generate human_like faces

# CelebA DCGAN Project

## Overview

This project implements a Deep Convolutional Generative Adversarial Network (DCGAN) to generate realistic celebrity face images using the CelebA dataset. The DCGAN consists of a generator and a discriminator trained in an adversarial manner.

## Table of Contents

- [Dataset](#dataset)
- [Data Preprocessing](#data-preprocessing)
- [Generator and Discriminator Architecture](#generator-and-discriminator-architecture)
- [Training](#training)
- [Results](#results)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Dataset

The CelebA dataset is used in this project, containing labeled images of celebrity faces. The dataset is loaded and processed using PyTorch's DataLoader.

## Data Preprocessing

Images are preprocessed by resizing and normalizing them to a range of -1 to 1. The preprocessing steps ensure compatibility with the DCGAN architecture.

## Generator and Discriminator Architecture

The DCGAN consists of a Generator responsible for generating realistic images from random noise and a Discriminator that learns to distinguish between real and generated images. The architecture details are specified in the `Generator` and `Discriminator` classes.

## Training

The models are trained using an adversarial loss function. The training loop includes alternating between updating the Discriminator and updating the Generator. The training progress is monitored and losses are displayed.

## Results

Generated samples are saved during training and can be visualized using the `view_samples` function. These images showcase the progress of the Generator in creating realistic celebrity faces.

## Usage

To use this project:

1. Clone the repository.
2. Ensure dependencies are installed (specified in the next section).
3. Run the Jupyter notebook or script to train and evaluate the DCGAN.

## Dependencies

- Python 3.x
- PyTorch
- Matplotlib
- NumPy

Install dependencies using:

```bash
pip install -r requirements.txt

