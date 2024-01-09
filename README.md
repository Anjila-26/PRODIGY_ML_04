# Hand Gesture Recognition and Data Collection

## Overview

This project consists of two main parts: `Data_collection.py` and `check.py`. The former is responsible for capturing hand gesture images, saving them to a specified directory, while the latter uses a trained model to classify hand gestures in real-time using a webcam.


## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/hand-gesture-recognition.git
    cd hand-gesture-recognition
    ```

## Usage

### Data Collection

Run `Data_collection.py` to capture hand gesture images. Adjust the folder path and other parameters as needed.

Press 's' to save the current hand gesture image to the specified folder.

## Model Training
Ensure you have the necessary dataset in the appropriate folder structure. Use load_data from hand.ipynb to load and preprocess the data. Train the model using the provided architecture in the notebook.

## Real-time Classification
Run `check.py` for real-time hand gesture classification.

## File Descriptions
**Data_collection.py**: Captures hand gesture images and saves them to a specified directory.
**hand.ipynb**: Jupyter notebook containing functions for loading and preprocessing hand gesture dataset, as well as model training.
**check.py**: Real-time hand gesture classification using a trained model.




