# DLTraining

View the slides for this training [here](https://rob-fletcher.github.io/DLTraining/)


## Installation Instructions

Make sure that miniconda is installed.

### Setup the Conda environment

```bash
conda env create -f environment.yml
```


## Lessons

### [Intro To ANNs](IntroToANN/IntroToANN.slides.html){:target="_blank"}
In this lesson we will cover the basics of Artificial Neural Networks, the important math behind how and why they work
and then do a quick survey of common types of ANNs and what they are used for.

### [Intro To Pytorch](IntroToPytorch/IntroToPytorch.slides.html){:target="_blank"}
We will begin to cover the basics of Pytorch and its core components. We will then look at how these components can
be used to create a computation graph and how the Optim package allows us to backpropagate through it.

### [Hands on with Pytorch](https://github.com/Rob-Fletcher/DLTraining/tree/master/HandsOn_1){:target="_blank"}
The notebooks provided in the repo show a simple example of using deep learning to solve the classification problem
with the MNIST and FashionMNIST datasets. 

[Convolutional Neural Networks (Work in Progress)](CNNs/CNNs.slides.html){:target="_blank"}