# 🚀 MilitaryObjectDetection 🌟

A Deep Learning Project Produced by 
Arjun Rajpal

Andrew Shao

Jai Gupta


##  Contents of Read Me 
1. About Repo/Motivation
2. About the Data
3.  Files/Dirs and what they do
4. Set up and using

# About this repo/Motivation

On the battlefield, soldiers at times can find it difficult to identify potential targets in the fog of war. It can be hard to spot a tank hiding in a well-placed bush or an aircraft strafing through heavy smog, which can lead to surprise attacks and potential casualties. Our project will examine ways to make near real-time identification of aircraft with various data augmentation techniques in order to potentially address this difficulty. In short, we want to find and evaluate different ways of performing near real-time object detection based on both speed of detection and accuracy.


## Data (Data files were too large to include in this repo)
1. Military Aircraft Dataset (https://www.kaggle.com/datasets/a2015003713/militaryaircraftdetectiondataset)
   
   a. This dataset contains images for 43 different types of military aircrafts from a variety of angles and locations. This includes bounding given in PASCAL VOC format to identify where the objects lie within each image. These images are sourced from google. This image dataset meets our requirements because it contains images containing military aircraft. Moreover, we will be doing substantial augmentation to expand this dataset. In total there are 19746 images in the dataset spread across 43 different classes. This distribution of images by class is given in the image below.

![image](https://github.com/ArjunRajpal123/MilitaryObjectDetection/assets/81884929/a56138c8-790b-4e28-9088-6b17cee1564b)

## Files/Dirs/Organization
```
\eda.ipynb - python notebook for all of our inital eda on the military aircraft dataset

\eda_model_trainCNNs.ipynb - python notebook to do more eda + train our Resnet, VGG and Alex Net Models

\evaluation_on_original.ipynb - evaluation code for our model (class accuracy/precision)

\visualization.ipynb - overall model performance visualizations

\FasterRCNNModel_training.ipynb - training file for Faster RCNN model

\video_processing.ipynb - file to evaluate all of our models on the video analysis aspect

\videos - a place to store desired videos to be processed - video file auto downloads so expect this to be empty upon cloning this repo

\models.zip - a place to store models which are finished training **MUST UNZIP FIRST**
```

### Special Note on Directories: Our models themselves were too large to upload to git hub so the models folder which is zipped up should be unzipped by the following command
```
unzip models.zip
```
### Likewise, since the dataset was too large to upload one must download from the link about and extract to a cloned version of the repo (you know you have done it right when the file folder archive is present)


# Set up and Running
Note Since we were using colab a lot of the commands which were used to install libraries are included in the notebooks
1. First download data from link
2. Unzip model.zip into root directory
3. Run desired files
 

## Quick Note

This repo has code which depends on hardware (GPUs) and it is recomended that one uses this repo in a Google Colab type enviroment as that is where these files were developed.
