# Automatic recognition of Human Disease using radiological Data


Automatic recognition of human disease using radiological data and machine learning is a field of medical imaging that aims to use machine learning algorithms to assist in diagnosis and treatment.

## Model_1
![Alt text](https://media.springernature.com/full/springer-static/image/art%3A10.1038%2Fs41598-020-79243-9/MediaObjects/41598_2020_79243_Fig1_HTML.png "Model")

## Model_2
![Alt text](https://ars.els-cdn.com/content/image/1-s2.0-S2589555922000155-gr2.jpg "Model2")

## Model_3
![Alt text](https://journals.plos.org/plosone/article/figure/image?download&size=large&id=10.1371/journal.pone.0242535.g003 "Model3")



## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install Python3.

```bash
pip install Python
```

## Usage

```python
import flask

import os
import numpy as np

# Keras
from tensorflow.keras.models import load_model
from tensorflow.keras.preprocessing import image

# Flask utils
from flask import Flask, request, render_template
from werkzeug.utils import secure_filename
import tensorflow_hub as hub

```

## Working Steps

1.Collect data: Gather a large and diverse dataset of radiological images and associated metadata. 

2.Preprocess the data: Clean and normalize the data to ensure that it is consistent and compatible with the machine learning algorithms being used.

3.Select a machine learning algorithm: Choose a machine learning algorithm used in medical imaging include deep learning models such as convolutional neural networks (CNNs).

4.Train the algorithm: Train the algorithm using the preprocessed dataset.

5.Evaluate the algorithm: Evaluate the performance of the algorithm on a validation dataset to ensure that it is accurate and reliable.
Test the algorithm: Test the algorithm on a separate test dataset to verify its performance and generalizability.

6.Integrate the algorithm: Integrate


