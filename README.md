# Simpsons Characters Classification Project

This project aims to classify Simpsons characters using deep learning techniques. The dataset used for this project can be found [here](https://www.kaggle.com/datasets/alexattia/the-simpsons-characters-dataset). Please note that on Kaggle, the folder containing the training data is nested within itself, so make sure to move the files before starting or navigate into the folder.

## Data Processing

In the `Data_processing.ipynb` file, the following steps are performed:
1. Count the number of images for each class in the training data.
2. Augment the dataset to address the imbalance.
3. Obtain a more balanced dataset and save it in a folder.

## Model Training and Evaluation

In the `SimpsonsClassification_test.ipynb` file, the following tasks are carried out:
1. Read the dataset.
2. Create data loaders for training and validation data.
3. Train the model and display metrics for the validation data.
4. Test the model on the test data.

## Requirements

The necessary libraries for this project are listed in the `requirements.txt` file.

Feel free to explore the project and improve the classification of Simpsons characters!
