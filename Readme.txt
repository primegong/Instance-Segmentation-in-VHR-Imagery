
The iSAID-Reduce100 dataset is a reduced version of the iSAID dataset for instance segmentation on remote sensing imagery. 
The dataset is composed of a training set and validation set. For each category, there are 100 training images and ~100 validation images.
The pixel size of the image is 512.

The iSAID-reduce100.zip is organized by two folders: train-100 and val-100. In each folder, files are stored by category. 
For each image, there is an associated label image and yaml file, recoding the instance information. 

It can be directly used for region-based instance segmentation network, such as Mask R-CNN. 
Unzip the .rar file and put it where you want. Then you can start training models with this dataset immediately.
