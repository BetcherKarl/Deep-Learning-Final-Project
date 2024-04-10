# Deep-Learning-Final-Project
Karl Betcher and Aaron Cherney

## Dataset
The [dataset](https://www.kaggle.com/datasets/gpiosenka/cards-image-datasetclassification) we are using contains thousands of pictures of playing cards. There are three folders in the dataset (train/test/valid) and each contains 53 subfolders, one for each card in a standard deck.

## Model
Throughout the project, we trained several models to classify the playing cards, and they all abide by the following structure:
- Input: 224x224x3 image or 150528 features (if it is flattened)
- Output: 18 features
  - 13 for the card number (A, 2-10, J, Q, K)
  - 4 for the card suit (hearts, diamonds, clubs, spades)
  - 1 for Jokers
Output: [ace, two, three, four, five, six, seven, eight, nine, ten, jack, queen, king, hearts, diamonds, clubs, spades, joker]
