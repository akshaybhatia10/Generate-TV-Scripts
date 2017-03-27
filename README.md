# Generate-TV-Scripts
## Udacity Deep Learning Nanodegree Foundation

### Install

This project requires **Python 3** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Tensorflow](http://tensorflow.org/)


You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html)

If you do not have Python installed yet, it is highly recommended that you install the [Anaconda](http://continuum.io/downloads) distribution of Python, which already has the above packages and more included. 


### Run

In a terminal or command window, navigate to the top-level project directory  (that contains this README) and run one of the following commands:

```bash
ipython notebook dlnd_tv_script_generation.ipynb
```  
or
```bash
jupyter notebook dlnd_tv_script_generation.ipynb
```

This will open the Jupyter Notebook software and project file in your browser.

## About

In this project, we will generate our own [Simpsons](https://en.wikipedia.org/wiki/The_Simpsons) TV scripts using RNNs. We will be using part of the [Simpsons dataset](https://www.kaggle.com/wcukierski/the-simpsons-by-the-data) of scripts from 27 seasons. The Neural Network  will generate a new TV script for a scene at [Moe's Tavern](https://simpsonswiki.com/wiki/Moe's_Tavern).

We will be using a subset of the original dataset. It consists of only the scenes in Moe's Tavern. This doesn't include other versions of the tavern, like "Moe's Cavern", "Flaming Moe's", "Uncle Moe's Family Feed-Bag", etc

