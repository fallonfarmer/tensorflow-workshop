# TensorFlow tutorial
[Slides and code](goo.gl/nrdsxM)
[Git repo](https://github.com/random-forests/tensorflow-workshop.git)
[Open Source Models](github.com/tensorflow/models)

# Part 1 - Concepts
Use Cases:
* distinguishing between apple and orange using color of pixels
* distinguishing between similar dog types (malamut and huskey)
* generating a summary for bodies of text

## What is Tensorflow?
* Google's machine learning library, particulary *Deep Learning*
* Tensor - multidimensial array
* Flow - graph of operations
* Computation = tensorflow graph (nodes and edges

## Architecture
* Kernels: lowest level (CPU, GPU, TPU)
* Operations: add, mul, Print, reshape ,etc.
* Distrbuted Execution System
* Front-end: *C++, Python*, Java, JavaScript, Ruby, etc.

## Toolkit
* Python API
* layers, losses, metrics
* tf.contrib.learn (inspired by scikitlearn)

## How does it work?
1. create variables
2. build operations to do things with variables
3. create session for execution environment
4. initialize variable by running the session
    * Fun fact: initialize_all_variables doesn't actually initialize the variables, you must call the init operation in session.run(init)

## Creating Linear Regression Model - Pattern
1. inference - predict y
2. loss - quantify
3. eval - accuracy
4. train - improve prediction with training data
    * Learning rate = 0.5, when in doubt, half the learning rate and try again
**Check this out: Tutorial - tensorflow mechanics 101**

## Tensorboard
tensorboard --logdir .

##### google: docker attach bash running container
docker exec -i -t [id] /bin/bash

## TF Learn (similar to scikitlearn)

## [TensorFlow Playground](playground.tensorflow.org)
javascript DEEP neural network that you can experiment with in your browser
at the lowest layer, linear classifier


using for feature extraction
deep learning - use raw pixel values and let the classifier automatically find useful features
hypertune the parameters

Don't trust but verify

**Check this out: Stanford cs231n - Convolutional Neural Networks for Visual Recognition**

