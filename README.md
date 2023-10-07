# Face-Generation-using-DCGAN
A Generative Adversarial Network to generate faces

## Topic
In this notebook I will experiment with generative AI, I will specifically be using Deep Convolutional Generative Adversarial network or DCGAN to try and generate human faces from noise
 data. First of all I will need to detect and crop people's faces that are present in my pictures dataset. After that I will need to use two adversarial networks: a generator that would 
 generate fake pictures and a discriminator that would classify those generated pictures as well as real pictures to be either real or not. Finally after training both models I will try 
 to use the generator to make up news images based on what it has learned during the training. So let's get started !

 ## Objectives
- Detect human faces in pictures
- Build two adversarial networks and train them
- Produce images using the Generator network

## Summary
- Importing libraries
- Detecting and cropping faces
- The dataset
- The Discriminator
- The Generator
- Building the network
- Specifying losses
- Training the network
- Inference
- Conclusion

## Libraries
- Numpy
- Matplotlib
- Pickle
- Torch
- CV2
- Glob

## Data source
https://www.kaggle.com/datasets/ashwingupta3012/male-and-female-faces-dataset?fbclid=IwAR01HFus7a9wo1eYk0zNT3B_DOu_g4wcAkw9mqlDqOkX1lKsXpZFh_BQNMs
