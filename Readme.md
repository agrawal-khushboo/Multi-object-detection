# Team Error404: Team Not Found

## Team Members
* Aiman Jabaren- ajabren@ucsd.edu
* Aditi Tyagi- adtyagi@ucsd.edu
* Khushboo Agrawal - khagrawa@ucsd.edu
* Hayk Hovhannisyan- hhovhann@ucsd.edu

## Objective
In the following project, we aim to implement the YOLOv2 algorithm for the multi-opject detection on the images

## Dataset
In order to run the code in this repository, you will need to install the following dependencies:
* PASCAL VOC'12 dataset (taken from the server)
* Test Data set (given in the gdrive link provided below)
* Trained weights (given in the gdrive link provided below)
* Pretrained weights (given in the gdrive link provided below)
* Test images (given in the Data folder)

## File Structure

* **Multi-object-detection.pdf**
This is the final report. 

#### _Demo_
* **Code_Demo.ipynb**
This Jupyter notebook contains the demo.  

#### Requirement to run the demo 
* 

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
* **4training.ipynb**
This jupyter notebook loads the model and pretrained weights and train the network. 

#### Post Training


#### _Logistics and Data_

* **data/ folder**
The folder contains all the csv files of the politicians containing the tweets and other attributes

* **file/ folder**
