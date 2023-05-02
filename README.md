# Brain-Tumor-Segmentation-using-U-Net
**U-Net** is a **convolutional neural network** architecture used for **image segmentation** tasks, such as medical image segmentation or object detection in computer
vision.
The architecture was first introduced in the 2015 paper "U-Net: Convolutional Networks for Biomedical Image Segmentation" by Olaf Ronneberger, Philipp Fischer, and Thomas Brox.

The U-Net architecture consists of a contracting path, which captures context and reduces the spatial resolution of the input image, and an expansive path, 
which produces the segmentation mask. The contracting path is made up of convolutional layers with a small receptive field, followed by max pooling layers. 
The expansive path is made up of upconvolutional layers with a large receptive field, which increases the spatial resolution of the feature maps.


![u-net-architecture](https://user-images.githubusercontent.com/85625650/235731836-183b8234-ad76-48d2-afc2-23af18690d03.png)
