# CE888
CE888 repository
 
 1) CE888 Assignment 2:
 
 Please note that the link to the code is as follows:
https://github.com/RitikaVinayakamurthy/CE888/blob/main/CE888Assignment2/2003204Assignment%202.ipynb
 
 2) The 'Fire vs No Fire" dataset can be found in the below link to download:
https://ieee-dataport.org/open-access/flame-dataset-aerial-imagery-pile-burn-detection-using-drones-uavs

3) Code descrition:
* The files are imported from into the dataset from the google drive which is done separately for training and test sets
* Please load the dataset onto your google drive before running the code 
* We first look into the Training folder which consists of two folder which is fire and No Fire.
* The number of images in Fire and No Fire folders are checked for imbalance in the dataset
* Random images are checked and labeled for refernecing
* A single image has been read using PIL function to check dimensions and mode.
* The files have been renamed for ease in analysis
* new empty directoreis are created for storing the newly named images
* Selected amount of images are selected for train, test and validation to get rid of the imbalance
* The images are labled to Fire and No fire
* The dataset is split into labels and features for fitting the models
* Three different models are implemented for the same dataset and accuracy is calculated for comparing them

