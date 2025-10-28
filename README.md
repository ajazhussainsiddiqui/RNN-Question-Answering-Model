# RNN-Question-Answering-Model

This project builds a simple Recurrent Neural Network (RNN) in PyTorch for question-answering on a small Q&A dataset (e.g., trivia questions like "What is the capital of France?").

## Key Features
- Dataset: 90 Q&A pairs (questions and answers).
- Basic RNN model for sequence prediction.
- Trained on tokenized text inputs.

## Setup
1. Install dependencies: `pip install torch pandas scikit-learn`.
2. Load the CSV dataset and train the RNN.

## Results
- Model processes sequences for answer generation.
- Example: Input "What is the capital of France?" → Output "Paris".
- Due limitations gets error like "Who directed the movie 'Dark knight ?"  → Output "batman" 
