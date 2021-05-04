# Face-Generation-using-DCGAN-Udacity
In this project, I defined and trained a DCGAN on a CelebA dataset with the goal of  generating new images of faces that look as realistic as possible.

## Dataset

[CelebFaces Attributes Dataset (CelebA)](https://s3.amazonaws.com/video.udacity-data.com/topher/2018/November/5be7eb6f_processed-celeba-small/processed-celeba-small.zip)

## Contents
- Pre-processed Data
- Create a DataLoader
- Define the Model
- Discriminator
- Generator
-  Weights Initialization
-  Build complete network
- Discriminator and Generator Losses
- Optimizers
- Training
- Training Loss 
- Generator samples from training

## Hyperparameters used:
> Batch Size = 32
> Generated Image Size = 32 x 32
> Eength of latent vector z = 100
> Number of Filters in Discriminator's first hidden layer = 32
> Number of Filters in Generator's first hidden layer = 32
> Initial Learning Rate, [beta1, beta2] = 0.0005, [0.1, 0.9]
> Number of Epochs = 10
