# Semantic Segmentation

[image1]: ./imgs/img_01.png "image"
[image2]: ./imgs/img_02.png "image"
[image3]: ./imgs/img_03.png "image"
[image4]: ./imgs/img_04.png "image"
[image5]: ./imgs/img_05.png "image"

### Introduction
Semantic segmentation attempts to partition the image into semantically meaningful parts, and to classify each part into one of the pre-determined classes. 

In this project the goal is to label the pixels of a road in images using a Fully Convolutional Network (FCN) i.e. to train segmentation networks, which paint each pixel of the image a different color, based on its class. Use segmented images to find free space on the road.

Results:

![alt text][image1]
![alt text][image2]
![alt text][image3]
![alt text][image4]
![alt text][image5]

### Setup
##### Frameworks and Packages
Make sure you have the following is installed:
 - [Python 3](https://www.python.org/)
 - [TensorFlow](https://www.tensorflow.org/)
 - [NumPy](http://www.numpy.org/)
 - [SciPy](https://www.scipy.org/)
##### Dataset
Download the [Kitti Road dataset](http://www.cvlibs.net/datasets/kitti/eval_road.php) from [here](http://www.cvlibs.net/download.php?file=data_road.zip).  Extract the dataset in the `data` folder.  This will create the folder `data_road` with all the training a test images.

### Start
##### Run
Run the following command to run the project:
```
python main.py
```
**Note** If running this in Jupyter Notebook system messages, such as those regarding test status, may appear in the terminal rather than the notebook.
