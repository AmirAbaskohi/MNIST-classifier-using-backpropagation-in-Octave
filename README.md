# MNIST classifier in Octave

This is EX4 for Andrew Ng Coursera machine learning course which represents MNIST data classifier in Octave.

## What is MNIST dataset?
The MNIST database (Modified National Institute of Standards and Technology database) is a large database of handwritten digits that is commonly used for training various image processing systems. The database is also widely used for training and testing in the field of machine learning. It was created by "re-mixing" the samples from NIST's original datasets. The creators felt that since NIST's training dataset was taken from American Census Bureau employees, while the testing dataset was taken from American high school students, it was not well-suited for machine learning experiments. Furthermore, the black and white images from NIST were normalized to fit into a 28x28 pixel bounding box and anti-aliased, which introduced grayscale levels.

<img src="./MnistExamples.png">

## What is the goal?
Read a new image, find its class which means to recognize number.

## How to run it?
To run, first you need to install `Octave` with version `>=3.8`. To run you can easily use below command:

```
octave ex4.m
```

## Dataset files
Dataset files are `.mat` files with names: `ex4data1.mat` and `ex4weights.mat`.


*Made by Amirhossein Abaskohi*
