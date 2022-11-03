Steps to train with the VOC2007 dataset: 
1. Download the dataset and place it in a folder

2、Run write_txt.py to generate the text files for training and testing

3、Run train.py to start training

Training with your own training set: 1.

1、Put the xml file into \VOCdevkit\VOC2007\Annotations

2、Put the jpg files into \VOCdevkit\VOC2007\JPEGImages

3、Change the VOC_CLASSES in write_txt.py

4、Change the CLASS_NUM in yoloData.py, yoloLoss.py and new_resnet.py

5. Run write_txt.py to generate the text files for training and testing

6、Run train.py to start training

This is a YOLOv1 based on the dataset VOC2007.
If we want to train it to recognize different kinds of waste to do waste sorting, we need the data of waste and change the class_set and even the size of tensor. (This tensor is 7*7*30 which can recognize 20 classes)

reference:
https://github.com/inging550/YOLOV1-pytorch
