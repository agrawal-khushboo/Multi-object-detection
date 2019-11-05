
## Objective
In the following project, we aim to implement the YOLOv2 algorithm for the multi-object detection on the images

## Dataset
In order to run the code in this repository, you will need to install the following dependencies:
* PASCAL VOC'12 dataset (taken from the server)
* Test Data set (link provided below)
* Trained weights (given in the gdrive link provided below)
* Pretrained weights (given in the gdrive link provided below)
* Test images (given in the Data folder)

## File Structure

* **Multi_object_detection.pdf**
This is the final report. 

#### _Demo_
* **demo.ipynb**
This Jupyter notebook contains the demo which loads 5 images given in the data folder which were extracted from the test set. The test set is a file folder and could not be pushed on GitHUb. Hence, please download the folder from the drive. 
Instructions to run the demo file are given below:

#### Requirement and how to run the demo 
* Please download all the other supporting files given on the github to run the demo file. 
* Please download the trained weights from the files folder (gdrive link given below) and add to the 'data' folder. 
* The demo file reads the images from the test folder (which are 5 images extracted from the test set) to ease the running of the code. 
* The demo file can be tested for the test data too. To do so, please download the data (link given below) and put the VOC2012  with all its content in the same directory as all the other files. 


#### Before Training 
* **data_r.ipynb**

The jupyter notebook contains the necessary functions for reading, scraping the images and encoding them. This also contains functions for findng the anchor boxes and and its height and width values by running K means on it.

* **model_r.ipynb**

The jupyter notebook initializes the YOLOv2 network.

* **weight_r.ipynb**

The jupyter notebook contains function for assigning the pretrained weights and intializing the weight to the last layer.

* **loss_r.ipynb**

The jupyter notebook conatains functions for evaluating the losses which is called for training.

#### Training
* **training.ipynb**

This jupyter notebook loads the model and pretrained weights and train the network. For running the file please download the supporting files given on the github as well as the pretrained weights (link to gdrive given below)

#### Post Training

* **evaluate.ipynb**

The jupyter notebook contains functions for generating the heat map and evaluating the precison recall curve as well as mean average precsion on the test set. 

* **evaluate_support.ipynb**

The jupyter notebook contains supporting functions to run the evaluate.ipynb file. 

#### _Logistics and Data_

* **data/ folder**

The data contains 5 images which were taken from the test set to run the demo file. 

* **file/ folder**

gdrive link- https://l.facebook.com/l.php?u=https%3A%2F%2Fdrive.google.com%2Fopen%3Fid%3D1Hw37jAeLokLCfvomO___rNjsbdqVin14%26fbclid%3DIwAR3ySD6XEMMGwslZYaopsc5_6Tp4Ax5aA_L-ScF_pj64wS03-q1kUiThBBU&h=AT0adxyEFdlNPG1b0u2otf6ODY-OosbgVm8bnfc-fnvAvh72QMn-bIXacD0b11HKbdq5hJwbrtMe08ZhQiAm--gwS2gUB6KnbSLEA22kpZV2e8bROKTGVXtxlva-NPrgvJ5nZjcBd9cX2GpWdwRW_r9cZ-k

The file contains two files which are 

* trained_weights.h5 - They are trained weights which is used for evaluation and prediction 
* yolov2weights.h5 - The weights are used to assign the pretrained weights for training the network.


* **Test set**

From the link please download the VOC2012 test data set. 

https://pjreddie.com/projects/pascal-voc-dataset-mirror/?fbclid=IwAR1PPLV2MuhqejhEFxl0MW3VH2yGq_i-S215ysJSmAL9OGAhfkal0ie07wY

