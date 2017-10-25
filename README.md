# A Convolutional Neural Network Dog Breed Classifier

## Overview
This project analyzes several different CNN models for their ability to to recognize and identify dogs and humans. As input this project uses a custom [human dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip) and a custom [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip) - both provided by Udacity. This work was done to complete a project for the Udacity Artificial Intelligence Nanodegree (AIND). The original project instructions can be found in the `Project_Instructions.md` file.

## Requirements
Conda was used to setup an enviornment with all the needed libraries and the correct Python version. In the `/Requirements` folder are three different yaml files for the Windows, MacOS, and Linux operating systems. You can use the correct yaml file for your operating system to create your own Conda enviornment with the right setup. Take a look at the [Conda users guide](https://conda.io/docs/user-guide/index.html) to learn more.

The software requirements for the project are also listed in the `requirements.txt` file.

This project is designed to be run on a Computer containing a Nvidia GPU compatible with Tensorflow. Running this project only on a CPU will likely take a prohibitively long time.

# Usage
To run the project open and execute the dog app Jupyter Notebook. In the terminal execute:

`jupyter notebook dog_app.ipynb`

