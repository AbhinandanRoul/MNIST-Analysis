# MNIST-Analysis
The initial dataset was taken and a CNN with 4 Convolutional layers was trained. The given dataset with 40 images in one class was split into 35 images in training set and 5 images in validation set for each category. The model has an input image shape of 400x400x1 for faster training. After training the model on 62 classes we save it.

Later we load the model and change the output layer. We now require to have 10 layers as the MNIST has 10 categories. We use the previous model to retrain another model on the same network. We get better accuracy in training and validation set. 

Then, we use the model on standard MNIST data and found it to provide much better results.



