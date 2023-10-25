# Convolutional Autoencoder for Image Denoising

## AIM:

To develop a convolutional autoencoder for image denoising application.

## Problem Statement:
Autoencoder is an unsupervised artificial neural network that is trained to copy its input to output. An autoencoder will first encode the image into a lower-dimensional representation, then decodes the representation back to the image.The goal of an autoencoder is to get an output that is identical to the input. Autoencoders uses MaxPooling, convolutional and upsampling layers to denoise the image.
We are using MNIST Dataset for this experiment. The MNIST dataset is a collection of handwritten digits. The task is to classify a given image of a handwritten digit into one of 10 classes representing integer values from 0 to 9, inclusively. The dataset has a collection of 60,000 handwrittend digits of size 28 X 28. Here we build a convolutional neural network model that is able to classify to it's appropriate numerical value.
## Dataset:
![image](https://github.com/SOMEASVAR/convolutional-denoising-autoencoder/assets/93434149/6de7938a-5953-477e-b617-2fd13947b317)


## Convolution Autoencoder Network Model:

![image](https://github.com/SOMEASVAR/convolutional-denoising-autoencoder/assets/93434149/276b4852-4987-47bb-b246-976205dc76c4)


## DESIGN STEPS

### STEP 1:
Import the necessary libraries and dataset.
### STEP 2:
Load the dataset and scale the values for easier computation.
### STEP 3:
Add noise to the images randomly for both the train and test sets.
### STEP 4:
Build the Neural Model using
<ul>
Convolutional Layer
Pooling Layer
Up Sampling Layer.</ul>
Make sure the input shape and output shape of the model are identical.
### STEP 5:

### STEP 6:



## PROGRAM

Include your code here

## OUTPUT:

### Training Loss, Validation Loss Vs Iteration Plot:

![image](https://github.com/SOMEASVAR/convolutional-denoising-autoencoder/assets/93434149/cbb6f0b8-c727-44b5-a9a5-6532130b12f8)


### Original vs Noisy Vs Reconstructed Image:

![image](https://github.com/SOMEASVAR/convolutional-denoising-autoencoder/assets/93434149/8babed85-86dc-422a-8d7b-f673ae56fe7e)




## RESULT:
Thus we have successfully developed a convolutional autoencoder for image denoising application.
