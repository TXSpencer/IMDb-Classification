# Film Review Sentiment Classification

This project aims to classify film reviews as positive or negative based on their textual content using a neural network model implemented in Python using Keras.

## Getting Started

To run the code, follow these steps:

1. Install the required libraries by running `pip install -r requirements.txt`.
2. Run the `imdb_classification.ipynb` script.

## Code Description

The `imdb_classification.ipynb` script performs the following tasks:

1. Loads the IMDb dataset of film reviews using Keras.
2. Preprocesses the data to be used by a neural network model.
3. Builds and compiles a neural network model using Keras.
4. Trains the model on the training data and validates it on a validation set.
5. Evaluates the model on the test data.
6. Predicts the sentiment of a sample film review and prints the result.

## File Description

- `imdb_classification.ipynb`: The main Python script containing the code for data loading, preprocessing, model building, training, evaluation, and prediction.
- `README.md`: This file, providing an overview of the project and instructions for running the code.
- `requirements.txt`: A text file listing the required Python libraries and their versions.

## Usage

You can run the `imdb_classification.ipynb` script using Python. Make sure you have the required libraries installed, as listed in `requirements.txt`.

```bash
python imdb_classification.ipynb