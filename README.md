Title: Weed Detection

Description:

This code implements a deep learning model for semantic segmentation of maize fields using MATLAB. 
The model is trained to identify three classes: maize plants, weeds, and soil.

Dataset:

The dataset used in this project is gathered locally. 
It consists of resized images and their corresponding pixel labels. 
The pixel labels are stored in a separate folder named "resize_labels". 
The image and pixel label datastores are created using the MATLAB Image Processing Toolbox.

Code:
The code is implemented in MATLAB R2021a. The main file is named "Code.mlx". 

The code consists of the following steps:

  - Creation of imageDatastore and pixelLabelDatastore objects for the image and label datasets, respectively.
  - Splitting the dataset into training and validation sets.
  - Data augmentation using random patch extraction.
  - Defining the deep learning model architecture using convolutional and transposed convolutional layers.
  - Training the model using the training data and validating it using the validation data.
  - Saving the trained model which can then used by Matlab GUI.
  
Usage:
To run the code, open the file "Code.mlx" in MATLAB and run it. The output will be the trained model saved in the current directory.
Then we can open the matlab GUI to detect weed in a new picture/video.

