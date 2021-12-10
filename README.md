# Denoising Image with Autoencoder in PyTorch

The purpose of this repository is to build an autoencoder in PyTorch in order to perform denoising operation on images. For that purpose, it loads MNIST image datsets and adds noises to every image. Later, an autoencoder is built and trained to reproduce actual images from noisy images.

In short, this repository performs the following operations:
1. Loading the MNIST image dataset and exploring it along with visualization
2. Preparing a custom dataset in PyTorch to load the image dataset. This custom dataset creates a noisy version of each image where noisy images and original images serve as input data and labels in the training dataset
3. Loading the custom dataset using PyTorch dataloader as batches
4. Creating an autoencoder model to denoise image
5. Training the autoencoder model
6. Evaluating the model performance and plotting prediction results
