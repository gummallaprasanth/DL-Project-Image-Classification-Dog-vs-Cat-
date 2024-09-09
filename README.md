# Dog vs Cat Image Classification

## Overview

This project aims to classify images into two categories: dogs and cats. The classification model is built using 
a Convolutional Neural Network (CNN) with the help of deep learning libraries. 


## steps follwed in this Process

1. download the dataset using kaggle api.

2. Extracting the files from compressed  zip file

3. count the images in the dataset

4. importing the required libraries

* from PIL import Image

* import matplotlib.pyplot as plt

* import matplotlib.image as mpimg

* from sklearn.model_selection import train_test_split

* from google.colab.patches import cv2_imshow

5. creating a directory for the resized  images

6. resize the all images into same size dimensions and convert images into RGB format (beacuse model can understand eaisly and predict well)

7. create labels for images for prediction (cat-->0 and dog--->1)

8. check the dataset is balanced or not beacuse we are using only small amount like 2000 images beacuse it is a pretrained mode.

9. convert into numpy arrays and do scaling into a range of 0 to 1 for machine get eaisly understand and predict well.

10. Converting all the resized images to numpy arrays

11. split the dataset into x_test and x_train

12. bulding the neural network using CNN (in this we used mobilenet_model as Pretrained model for image classification).

13. creating sequential and adding layers and compile the model with adam optimzer for good prediction.

14. predict the test data and evaluate the model performence.

15. fially build a predictive system for the user if they want test the model.


