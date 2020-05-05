# Neuro 140: Biological and Artificial Intelligence 

This repository contains all code used for the neuro 140 final project. Below is a list of the files and their purpose. For all of the data preprocessing notebooks below please update directory paths as needed to upload data. 

## Data Processing 

resize_images.ipynb: This file takes in images from a local directory and converts them to a uniform size (256x256 pixels). 

png_to_jpg.ipynb: This file takes in images from a local directory and converts them from their original image format to the .jpg format. 

pair_images.ipynb: This file takes in two sets of images from a local directory and combines them into one image (512x256 pixels). 

enumerate.ipynb: This file takes in images from a local directory and enumerates their file title in order to be processed in Google Colab appropriately.

## Data Augmentation

In order to augment my initial curated custom dataset to have enough data pairs to train a deep learning framework I used the scripts from the following repository: (https://github.com/codebox/image_augmentor#examples)

## Building GAN Models

All general GAN models and Pix2Pix models used in this project were built and trained in Google Colab. 

The data used for initial testing came from the Pix2Pix publication data base of processed data: (https://people.eecs.berkeley.edu/~tinghuiz/projects/pix2pix/datasets/)

The GAN architecture itself was adapted from the Pix2Pix Tensorflow 2.0 Core which can be found here:
(https://github.com/tensorflow/docs/blob/master/site/en/tutorials/generative/pix2pix.ipynb)

For training the custom dataset I loaded my preprocessed data from a local repository into Google Drive and then wrote additional code in Google Colab to mount the that Drive and then pull and extract the zipped processed data for setup and training.

The zipped data files are too large to upload to GitHub. To get the data used in this project please email me at jordan.kruguer@gmail.com.





