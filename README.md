#Deep-Learning-Project
# ABSTRACT
Numerous endeavors have been made in the correct detection and segmentation of objects such that Deep Learning has reached a point of extracting excellent features of objects from an image and use those features for a plethora of tasks related to computer vision. Our work is divided into two parts. The first part is to detect individual fruits and obtain a pixel-wise mask for each detected fruit in an image. To this end, we have used a deep learning approach, named Mask-RCNN, which is a state-of-the-art instance segmentation framework, for the detection and pixel-wise segmentation of fruits on multi-class RGB images. The dataset being used for this task is “Fruit Recognition Dataset” containing multi-class images. The second part of this work is the classification of real vs fake fruits. For this, we have used “Hyperspectral & Color Imaging” dataset which contains hyperspectral images of 5 different fruit classes.

## Dataset Sources

[Fruit Recognition Dataset](https://zenodo.org/record/1310165)

[Hyperspectral & Color Imaging](https://sites.google.com/site/hyperspectralcolorimaging/dataset)

# Experiment 1(Fruits detection using Mask_RCNN)

## Dataset:
Total Classes: 5
Picture Dimensions: 320×258
Total number of images: 500

## Input Images
![](Images/Input_Images/apple.png)
![](Images/Input_Images/orange.png)
![](Images/Input_Images/mango.png)
![](Images/Input_Images/peach.png)
![](Images/Input_Images/tomato.png)

## Mask_RCNN Architecture

![](Images/Mask_RCNN.jpg)

## Results
### Output Images
![](Images/Output_Images/Apple.png)
![](Images/Output_Images/Orange.png)
![](Images/Output_Images/Mango.png)
![](Images/Output_Images/Peach.jpg)
![](Images/Output_Images/Tomato.jpg)

### Mean Accuracy Precision (mAP)

mAP:             (0.8897, 0.8897, 0.8873, 0.8822, 0.7629)
IOU threshold:   (0.5,    0.55,   0.6,    0.65,   0.7)






