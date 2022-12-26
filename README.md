# UCSD ECE228 Project (Team 47)

<p align="justify">
This project aims to implement real-time traffic sign detection and recognition. The first task to solve this problem would be to detect where the traffic sign is located in the picture taken by the dashboard camera, which is done by using a famous architecture called Faster R-CNN. The next task will be to classify the portion of the image that represents a traffic sign which we performed using a custom CNN architecture.
</p>

## Project Poster
<p align="center">
  <img width="1000" alt="image" src="https://user-images.githubusercontent.com/89351094/209574238-76bd4a55-3711-4029-ad8b-27ae0e31101b.jpg">
 </p>



## How to run the code

Run the -file 1- and -file 2- which will train the models and save them.

Run the -main execution- file which will print the accuracy comparison of classification of our model with the Faster R-CNN classification results. The details of the files are as below:

## There are three folders in total

### 1) Faster R-CNN
Files: 

Faster R-CNN Training.ipynb - This includes the complete model of Faster R-CNN (for Detection) along with the data loading and training. This will save the model in a pickle file after training is finished

all other .py files are helper files

Download full data from here: https://sid.erda.dk/public/archives/ff17dc924eba88d5d01a807357d6614c/FullIJCNN2013.zip

Full sized images need to be in this directory: /data/train/images
Rest of the files(gt.txt) and folders will go into: /data


### 2) CNN
Files:

CNN Training and Testing.ipynb - This includes the complete model of CNN (for Classification) along with the data loading and training. This will save the model in a pickle file after training is finished.

Download full data from here: https://sid.erda.dk/public/archives/daaeac0d7ce1152aea9b61d9f1e19370/GTSRB-Training_fixed.zip

unzip this inside the CNN folder

### 3) Main

This includes the main execution file along with three test images taken from youtube as screenshots.
It inludes the code integrading the effect of both the models that have been trained in two files. It also includes the accuracy check functions with relevant names.

