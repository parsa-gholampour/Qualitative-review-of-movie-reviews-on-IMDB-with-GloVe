# Text Processing and Sentiment Analysis

This repository contains a Jupyter Notebook for performing text preprocessing and sentiment analysis using the IMDB movie reviews dataset. The notebook demonstrates various Natural Language Processing (NLP) techniques and machine learning workflows.

## Features

- **Text Preprocessing**:
  - Cleaning and tokenization of text.
  - Removal of stopwords.
- **Embedding Techniques**:
  - Integration of GloVe embeddings for feature representation.
- **Dataset**:
  - IMDB movie reviews dataset for binary sentiment classification.
- **Data Splitting**:
  - Dividing the dataset into training and testing sets.

## Requirements

To run the notebook, the following libraries are required:

- Python 3.7+
- Jupyter Notebook
- pandas
- numpy
- nltk
- kagglehub

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   ```
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook source.ipynb
   ```
2. Follow the sections in the notebook to preprocess the data, load embeddings, and perform sentiment analysis.

## Dataset

The IMDB movie reviews dataset is used for sentiment analysis. It is a binary classification dataset with positive and negative reviews.

The dataset is automatically downloaded using the `kagglehub` package. Ensure you have appropriate access to Kaggle datasets before running the notebook.

## Embeddings

Pre-trained GloVe embeddings are used for representing textual data in a dense vector format. Download the embeddings file and place it in the specified directory before running the corresponding notebook cell.

## Results

The notebook evaluates the sentiment classification model on the test set and provides performance metrics like accuracy and F1 score.

## Contributing

Contributions are welcome! If you have suggestions or improvements, feel free to create a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for details.


