# Project : Image Captioning

## Description
In this project we combine Convolutional Neural Networks (CNN) and Recurrent Neural Networks (RNN) knowledge to build a deep learning model that produces captions given an input image. 

Image captioning requires that you create a complex deep learning model with two components: a CNN that
transforms an input image into a set of features, and an RNN that turns those features into rich, descriptive
language.

## Files
* `Notebook 0`: Explore MS COCO dataset using COCO API
* `Notebook 1`: Load and pre-process data from the MS COCO dataset and design the CNN-RNN model for automatically generating image captions
* `Notebook 2`: Training phase of the CNN-RNN model 
* `Notebook 3`: Using the previously trained model to generate captions for images in the test dataset.
* `data_loader.py` : Custom data loader for PyTorch combining the dataset and the sampler
* `vocabulary.py` : Vocabulary constructor built from the captions in the training dataset
* `vocab.pkl` : Vocabulary file stored to load it immediately from the data loader
