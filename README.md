# Neuro 140: Biological and Artificial Intelligence 

This repository contains all code used for the neuro 140 final project. Below is a list of the files and their purpose. For all of the data preprocessing notebooks below please update directory paths as needed to upload data. 

## Data Processing 

resize_images.ipynb: This file takes in images from a local directory and converts them to a uniform size (256x256 pixels). 

png_to_jpg.ipynb: This file takes in images from a local directory and converts them from their original image format to the .jpg format. 

pair_images.ipynb: This file takes in two sets of images from a local directory and combines them into one image (512x256 pixels). 

enumerate.ipynb: This file takes in images from a local directory and enumerates their file title in order to be processed in Google Colab appropriately.

## Data Augmentation

In order to augment my initial curated custom dataset to have enough data pairs to train a deep learning framework I used the scripts from the following repository: 
(https://github.com/codebox/image_augmentor#examples)

## Building GAN Models

All general GAN models and Pix2Pix models used in this project were built and trained in Google Colab. 

The data used for initial testing came from the Pix2Pix publication data base of processed data: (https://people.eecs.berkeley.edu/~tinghuiz/projects/pix2pix/datasets/)

The GAN architecture itself was adapted from the Pix2Pix Tensorflow 2.0 Port which can be found here:



