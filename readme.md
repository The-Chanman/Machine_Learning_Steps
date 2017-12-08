# Text Classification with Keras and TensorFlow ported to python3

## The original model was located here and only ran for python2
Blog post is [here](https://vgpena.github.io/classifying-tweets-with-keras-and-tensorflow/)


Data can be downloaded [here](http://thinknook.com/twitter-sentiment-analysis-training-corpus-dataset-2012-09-22/). Many thanks to ThinkNook for putting such a great resource out there.

## Installation

You need Python 3 to run this project;

### Training
When creating the net finishes, three new files should have been created: `dictionary.json`, `model.json`, and `model.h5`. You will need these to use the net.

### Classification
To use the net to classify data, run `loadModel.py` and type into the console when prompted. Hitting Enter without typing anything will quit the program.


###TODO
Port over to Keras.js
Write batch analysis
