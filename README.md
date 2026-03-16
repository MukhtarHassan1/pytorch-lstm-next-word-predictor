
# PyTorch LSTM Next-Word Prediction Model

This project implements a **neural language model for next-word prediction using PyTorch and LSTM networks**.

The model learns sequential patterns from text data and predicts the most probable next word given an input sequence.

---

## Project Overview

Language models are fundamental components of modern NLP systems such as chatbots, search engines, and generative AI models.

This project demonstrates how to build a **next-word prediction model from scratch using PyTorch**, including preprocessing, dataset creation, and neural network training.

---

## Key Features

* NLP preprocessing using **NLTK**
* Vocabulary construction from raw text
* Sequence generation for language modeling
* Custom **PyTorch Dataset and DataLoader**
* LSTM-based neural network architecture
* Training with **Adam optimizer and CrossEntropyLoss**
* Next-word prediction inference

---

## Model Architecture

The model uses an **embedding layer followed by an LSTM network** to capture sequential dependencies in text.

Architecture:

```
Embedding Layer → LSTM → Fully Connected Layer → Softmax
```

Example configuration:

```
Embedding(vocab_size, 100)
LSTM(100, 150)
Linear(150, vocab_size)
```

---

## Technologies Used

* Python
* PyTorch
* NLTK
* NumPy
* Jupyter Notebook

---

## Training Pipeline

1. Text preprocessing and tokenization
2. Vocabulary creation
3. Sequence generation
4. Padding sequences
5. Building PyTorch Dataset and DataLoader
6. Training LSTM model
7. Evaluating predictions

---

## Example Prediction

Input sequence:

```
"The course follows a"
```

Predicted next word:

```
"monthly"
```

---

## Installation

Clone the repository:

```
git clone https://github.com/YOUR_USERNAME/pytorch-lstm-next-word-predictor.git
```

Install dependencies:

```
pip install -r requirements.txt
```

---

## Run the Notebook

Start Jupyter:

```
jupyter notebook
```

Open:

```
PyTorch-LSTM-Next_Word-Predictor.ipynb
```

Run all cells to train and test the model.

---
