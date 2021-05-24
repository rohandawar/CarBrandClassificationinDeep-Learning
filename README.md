# CarBrandClassificationinDeep-Learning

In this project we would implement car brand classification using images of the car of 3 brands: Mercedes, Audi, and Lamborghini.

VGG-16 is a 16 layer deep Convolution Neural Network that can classify images into 1000 object categories.This data set includes Car images used for Brand Classification. Here, we have two folders namely train and test, each of them has three folders named Lamborghini, Audi, and Mercedes. I have used transfer learning here because it is very useful since most real-world problems typically do not have millions of labeled data points to train such complex models.

Here, we are using Keras because it enables fast experimentation with deep neural networks. We will build our model with the help of Resnet 50 as it can train deep neural networks with many layers.

We need to create new training samples from the ones we have, this process in known is Image Augmentation. This can be performed using Image Data Generator.

Furthermore, the dataset used here is from Kaggle, so the process of importing dataset from kaggle to google colab is also shared here.

Happy Learning!
