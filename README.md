# Dog Vision 🐶

An end-to-end multi-class dog breed classifier using TensorFlow 2.0 and TensorFlow Hub.

## Project Overview
Dog Vision aims to identify the breed of a dog from an image. This project utilizes deep learning and transfer learning to achieve high accuracy in multi-class classification tasks.

## Problem Statement
Given an image of a dog, the objective is to determine its breed out of 120 possible dog breeds.

## Data
The dataset is from Kaggle's [Dog Breed Identification competition](https://www.kaggle.com/c/dog-breed-identification/data) and consists of:
- 10,000+ labeled images for training
- 10,000+ unlabeled images for testing

## Evaluation
The model's predictions will be evaluated based on the probabilities assigned to each breed for the test images. Accuracy and other relevant metrics will be used for evaluation.

## Features
- **Input:** Dog images
- **Output:** Predicted probabilities for each of the 120 breeds

## Project Structure
- **/Dog-Vision/dog-breed-identification/**: Directory containing the dataset
- **/Dog-Vision/dog_vision.py**: This is the script for the Dog Vision Deep Learning Model

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
    ```sh
    pip install -r requirements.txt

    ```

3. Download the dataset from Kaggle and place it in the data/ directory

## License

This project is licensed under the MIT License - see the LICENSE file for details.


## Acknowledgements

- [Kaggle Dog Breed Identification competition](https://www.kaggle.com/c/dog-breed-identification/data)
- TensorFlow and TensorFlow Hub documentation and resources