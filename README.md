# Mole detection

- Repository: `challenge-mole`
- Type of Challenge: `Consolidation`
- Duration: `8 days`
- Deadline: `24/05/2022 4:30` **(code)**
- Presentation: `25/05/2022 1:30 PM`
- Challenge: Solo


## Mission objectives

- Be able to apply a CNN in a real context
- Be able to preprocess data for computer vision
- Be able to evaluate your model (split dataset, confusion matrix, hyper-parameter tuning, etc)
- Be able to visualize your model results and evaluations (properly labeled, titled...)
- Be able to deploy your solution in an simple APP locally or on Heroku

## The Mission

This is a job we received from the company "skinCare". The job entailed that we would develop a website that would be able to classify pictures of moles.

The dataset provided by the client is here https://www.kaggle.com/kmader/skin-cancer-mnist-ham10000

Possible disease states are "Melanoma", "Melanocytic nevus", "Basal cell carcinoma", "Actinic keratosis / Bowen’s disease (intraepithelial carcinoma)", "Benign keratosis (solar lentigo / seborrheic keratosis / lichen planus-like keratosis)", "Dermatofibroma", and "Vascular lesion". Approximately 10,000 images provided for training, 200 for validation, 1500 for test.


## Preprocessing:
I resize the images as the original dimension of images are 450 x 600 x3 which TensorFlow can't handle, so that's why we resize it into 100 x 75.

## CNN Model:
I used the Keras Sequential API, where you have just to add one layer at a time, starting from the input.
I need to set up a score function, a loss function and an optimisation algorithm.
Data Augmentation to avoid overfitting problem.
finally I fit the model.

## Model Evaluation:
In this step we will check the testing accuracy and validation accuracy of our model, plot confusion matrix!

## Results presentation: Web App
As mention before the idea is to generate a tool to predict the probability of a malign mole. To do it, I provide Web App.

The web app will have the possibility that a user upload a high quality image of an specific mole. The results will be a prediction about the probability that the given mole be malign in terms of percentage.


## Installation
## Python version
Python 3.7

## Packages used
Tensorflow

sklearn

pandas

numpy

matplotlib.pyplot

seaborn
