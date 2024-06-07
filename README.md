# Dog Vision 🐶

An end-to-end multi-class dog breed classifier using TensorFlow 2.0 and TensorFlow Hub.

## Project Overview
Dog Vision aims to identify the breed of a dog from an image. This project utilizes deep learning and transfer learning to achieve high accuracy in multi-class classification tasks.

## Problem Statement
Given an image of a dog, the objective is to determine its breed out of 120 possible dog breeds.

## Data
The dataset is from Kaggle's Dog Breed Identification competition and consists of:
- 10,000+ labeled images for training
- 10,000+ unlabeled images for testing

## Evaluation
The model's predictions will be evaluated based on the probabilities assigned to each breed for the test images. Accuracy and other relevant metrics will be used for evaluation.

## Features
- **Input:** Dog images
- **Output:** Predicted probabilities for each of the 120 breeds

## Project Structure
- **data/**: Directory containing the dataset
- **notebooks/**: Jupyter notebooks for data exploration and model training
- **scripts/**: Python scripts for preprocessing and model building
- **models/**: Saved trained models
- **results/**: Evaluation results and metrics

## Requirements
- TensorFlow 2.x
- TensorFlow Hub
- pandas
- matplotlib
- scikit-learn

## Setup
1. Clone the repository
   ```sh
   git clone https://github.com/yourusername/dog-vision.git
   
   ```

2. Install the required dependencies

