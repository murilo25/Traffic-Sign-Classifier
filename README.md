# Traffic Sign Classifier

This project uses a data set to train a LeNet convolutional neural network to classify german traffic signs

The goals/steps of this project are the following:
* Load the data set (see below for links to the project data set)
* Explore, summarize and visualize the data set
* Design, train and test a model architecture
* Use the model to make predictions on new images
* Analyze the softmax probabilities of the new images
* Summarize the results with a written report

### Data Set Summary & Exploration

It uses pandas library to calculate summary statistics of the traffic signs data set:

* The size of training set is 34799
* The size of the validation set is 4410
* The size of test set is 12630
* The shape of a traffic sign image is (32, 32, 3)
* The number of unique classes/labels in the data set is 43

Next figure presents an exploratory visualization of the data set. The number of samples for each class available in the training and test data set are represented in blue and red, respectively.

![alt text][./readme_images/histogram.png]

A random sample of images present in the data set can be visualized below:

![alt text][./readme_images/random_sample.png]


