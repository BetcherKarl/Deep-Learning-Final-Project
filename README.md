# Deep-Learning-Final-Project
Karl Betcher and Aaron Cherney

## Dataset
The [dataset](https://www.kaggle.com/datasets/gpiosenka/cards-image-datasetclassification) we are using contains thousands of pictures of playing cards. There are three folders in the dataset (train/test/valid) and each contains 53 subfolders, one for each card in a standard deck.

## Model
Throughout the project, we trained several models to classify the playing cards, and they all abide by the following structure:
- Input: 224x224x3 image
- Output: 53 values between 0 and 1, representing the model's confidence in each card in a standard deck



