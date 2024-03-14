Nearest Neighbor Classification Project.

Overview

This project implements nearest neighbor classification algorithms using L1 and L2 distances from a Machine Learning Fundamentals course in Edx: course Staff Instructor Sanjoy Dasgupta, Professor, Computer Science and Engineering Department, UC San Diego.
It aims to classify data points into different classes based on their similarities to training data.
It aims to sharpen the ability to program in Python and to use Jupyter notebooks. This can be obtained by taking the course DSE200x, Python for Data Science.
Familiarity with calculus, especially derivatives of single-variable and multivariate functions.

NN_MNIST.

In the project, we are going to use MNIST datasets to build a classifier that takes an image of a handwritten digit and outputs a label 0-9. We will look at a particularly simple strategy for this problem known as the nearest neighbor classifier.

To run this notebook you should have the following Python packages installed:
* `numpy`
* `matplotlib`
* `sklearn`
After we will build classifiers using the K-D tree and Ball tree to fasten the training of the classifier.

NN_SPINE.

In this notebook, we use nearest neighbor classification to classify back injuries for patients in a hospital, based on measurements of the shape and orientation of their pelvis and spine.

The data set contains information from 310 patients. For each patient, there are six measurements (the x) and a label (the y). The label has 3 possible values, `’NO’` (normal), `’DH’` (herniated disk), or `’SL’` (spondylolisthesis). 

