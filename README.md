# Semantic Segmentation
### Introduction
In this project I trained a Fully-Convolutional Neural Network to do semantic segmentation of roads.

![Semantic Segmentation][semseg]

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
Note that you may need to use a large GPU (~10 GB) to train the network

[semseg]: ./runs/1504491028.745012/um_000023.png "Semantic Segmentation"
