# CE888
CE888 repository
 
 1) CE888 Assignment 1:
 
 Please note that the link to the code is as follows:
 https://github.com/RitikaVinayakamurthy/CE888/blob/main/new/main/CE888Assignment1.ipynb
 
 2) The 'Fire vs No Fire" dataset can be found in the below link to download:
https://ieee-dataport.org/open-access/flame-dataset-aerial-imagery-pile-burn-detection-using-drones-uavs

3)Code descrition:
* The required files are imported first after which the glob funtion is used to retrieve the folder.
* We look into the Training folder which consists of two folder which is fire and No Fire.
* The number of images in Fire and No Fire folders are checked for imbalance in the dataset
* Random images are checked and labeled 
* A single image has been read using PIL function to check dimensions and mode.
* The file directory is allocated to a variable.
* The Image data generator is used for data augmentation and the parameter validation is set to 0.3 to split the data into training and validation i.e with 70-30% split.
* The training and validation sets are generated and ready to be implemented in the model.

