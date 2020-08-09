# Image Captioning

## Description
Predicting caption for a given image using Deep Learning methods provided in keras library to create model architecture and training our model over the dataset.

## Model Architecture

![alt text](https://github.com/Msq-9/image-captioning/blob/master/model/image_caption_model.png?raw=true)

## Pipeline followed :
1. Data Cleaning
2. Data preprocesing (images & captions)
3. Preparing data for training using python generator function
4. Creating word embeddings of the vocabulary
5. Creating model architecture
6. Training on dataset

## Prerequisites
Basic Deep Learning concepts like Multi-layered Perceptrons, CNN, RNN, Transfer Learning, Gradient Descent, Backpropagation, Overfitting, Probability, Text Processing, Python syntax and data structures, Keras library, etc.

## Software
- python 3.8.2
- keras 2.4.3
- tensorflow 2.3.0
- pandas 1.0.3
- numpy 1.18.4
- matplotlib 3.2.1
- pydot 1.2.3

## Dataset
Dataset for this project has been collected from kaggle : https://www.kaggle.com/shadabhussain/flickr8k .
This dataset contains around 8000 images and 5 captions per image.

However if we want to train on a larger dataset [Flickr 30k](https://www.kaggle.com/hsankesara/flickr-image-dataset) which contains 30,000 images or [MS COCO](https://cocodataset.org/) which contains 180,000 images.

## Future scope
- Assistive vision : Images could be captured in realtime, and the caption predicted through that image which describes the image 
could be converted into a voice message with help of an appropriate API. This voice message could helpful in guiding or describing
the scene to the blind.
- Images similar to a given picture could be found out by searching the predicted caption in an appropriate search engine.

## Pending work
- Accuracy & precision has to be measured, BLEU Score could be used to evaluate our results.
- This model can be deployed in an appropriate web app.
