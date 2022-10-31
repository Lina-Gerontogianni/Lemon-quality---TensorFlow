# Lemon-quality---TensorFlow
Binary image classification with Tensorflow '2.9.1'

Lemon images of good and bad quality - taken from a public Kaggle [dataset](https://www.kaggle.com/datasets/yusufemir/lemon-quality-dataset) - are used for fruit quality control. A basic yet complete pipeline for the classification analysis is formed (validation accuracy: 97.59%), including data pre-processing, data configuration, creation of the Convolution Neural Network etc.

In this repo you can the Python script is named as lemon_qlt_analysis along with two images - 16 lemon samples from the training set and the training/testing performance.

The dataset is comprised of 2076 images in total (1125 of good qualit, 951 of bad). For the constructed pipeline, the dataset folder should come in a format where two sub-directories are contained:

dataset/

    good_quality/
  
    bad_quality/
