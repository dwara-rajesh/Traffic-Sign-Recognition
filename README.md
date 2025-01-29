The aim of this project is to detect, categorize and recognize traffic signs.

The repository contains 2 images (.jfif and .png files), a trained model (.h5 file) and a script written and run in Jupyter 
Notebook (.ipynb file). 

The .ipynb file is made understandable and clear with each cell of the notebook solving an aspect of the entire project.
This script trains a model on the following German Traffic signs dataset obtained from the following link:
https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign

The above dataset has 39,209 images in the training set and 12,630 images in the testing/validation set.
The model was trained in the TensorFlow environment using Keras and a 2 layer convolution network, with fine tuned hyperparameters on augmented images.
