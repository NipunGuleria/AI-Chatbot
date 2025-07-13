# AI-Chatbot
This project is a simple yet effective AI-powered chatbot built using PyTorch for neural network modeling and Natural Language Processing (NLP) techniques from NLTK. The chatbot is trained on customizable intents defined in a JSON file and can be extended to trigger functions or actions based on user inputs.

🚀 Features

Intent classification using a fully connected neural network

Tokenization and lemmatization for text preprocessing

Bag-of-Words model for input vectorization

Easily extendable intent-action mappings

Supports custom responses and callable Python functions

Model training, saving, and loading functionalities


Model Architecture

Input Layer (Bag of Words vector)
    ↓
Fully Connected Layer (128 units, ReLU)
    ↓
Dropout (0.5)
    ↓
Fully Connected Layer (64 units, ReLU)
    ↓
Dropout (0.5)
    ↓
Output Layer (Softmax over intents)

