# Instance segmentation in VHR remote sensing imagery based on hard-to-segment instance learning and boundary shape analysis
We build the proposed approach on the successful Mask R-CNN, which is pretrained on the MS COCO dataset. The code is implemented as in \cite{matterport_maskrcnn_2017}.  
It can be directly used for region-based instance segmentation network.


# iSAID-Reduce100 dataset:

The iSAID-Reduce100 dataset is a reduced version of the iSAID dataset for instance segmentation on remote sensing imagery. 
The dataset is composed of a training set and validation set. For each category, there are 100 training images and ~100 validation images.
The pixel size of the image is 512.
![Instance Segmentation training data](assets/iSAID_trianing_dataset.png)

The iSAID-reduce100.zip is organized by two folders: train-100 and val-100. In each folder, files are stored by category. 
For each image, there is an associated label image and yaml file, recoding the instance information. 
Unzip the .rar file and put it where you want. Then you can start training models with this dataset immediately.

链接：https://pan.baidu.com/s/1rIhvJpmT9-KQV5OUOiIg6Q 
提取码：7bnz

@misc{matterport_maskrcnn_2017,
  title={Mask R-CNN for object detection and instance segmentation on Keras and TensorFlow},
  author={Waleed Abdulla},
  year={2017},
  publisher={Github},
  journal={GitHub repository},
  howpublished={\url{https://github.com/matterport/Mask_RCNN}},
}
