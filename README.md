# Next-Token-Prediction-using-Transformer-Models
## Overview
This project explores next-token prediction using both a baseline model and a Transformer-based model. The goal is to build, train, and evaluate models on tokenized datasets to understand how well they can predict subsequent tokens in a sequence.
The project follows these key steps:
- Dataset loading and preprocessing
- Baseline model creation and training
- Transformer model implementation and training
- Evaluation and comparison of both models

## Structure

- Dataset, Tokenization and Preprocessing: Load and tokenize a dataset using HuggingFace's tools.
- Baseline Next-Token Prediction Model: A simple model using embedding and linear layers.
- Transformer-Based Next-Token Prediction: A more sophisticated architecture using attention mechanisms.
- Analysis and Comparison: Visualizations and performance comparisons of the models.

## Libraries Used

- torch, torch.nn
- transformers (Hugging Face)
- datasets
- matplotlib
- math, time, collections

## Running the Project

- Clone the repository or open the notebook in a Colab environment.
- Ensure dependencies are installed:
- pip install torch transformers datasets matplotlib
- Run the notebook cells sequentially.

## Results

The notebook includes detailed plots and evaluations for:
- Loss vs. Epochs
- Sample predictions
- Model comparison insights
