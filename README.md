# Monet-CycleGAN


This repository contains the implementation of a CycleGAN model for unpaired image-to-image translation, based on the paper "Unpaired Image-to-Image Translation using Cycle-Consistent Adversarial Networks" by Zhu et al. (2017). The project focuses on translating images between two domains: photos and Monet paintings.

## Features

- **Generators**: ResNet-based architecture for transforming images between domains.
- **Discriminators**: PatchGAN-based architecture for distinguishing real and generated images.
- **Cycle Consistency**: Ensures that translations from one domain to the other and back result in the original image.

## Usage

1. **Dataset Preparation**:
   - Load the datasets of Monet paintings and photos.
   - Batch the datasets for training.

2. **Model Training**:
   - Compile the CycleGAN model with appropriate optimizers and loss functions.
   - Train the model using the prepared datasets.

3. **Evaluation**:
   - Visualize the results of the image translation process.

## Code Structure

- **Data Loading**: Functions for loading and batching datasets.
- **Model Definition**: Classes and functions for building the CycleGAN model.
- **Training**: Code for compiling and training the model.



## Acknowledgements

This project is based on the CycleGAN architecture introduced by Zhu et al. in their 2017 paper.

