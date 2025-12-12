# Text Summarization Using Pre-trained Models

This repository demonstrates how to perform **automatic text summarization** using **pre-trained Transformer models** (such as BART or T5) from the Hugging Face `transformers` library.  
It includes data preprocessing, tokenization, model fine-tuning (optional), and inference on new text inputs.

---

## Project Overview
Text summarization is the task of generating a short and coherent summary of a longer text document.  
This notebook explores how to:
- Use a pre-trained summarization model (e.g., BART, T5)
- Tokenize and preprocess text datasets
- Train or fine-tune the model on custom data
- Generate summaries and evaluate model performance

---

## Features
- Support for multiple pre-trained models (`facebook/bart-large-cnn`, `t5-small`, etc.)
- Easy dataset loading using `datasets` from Hugging Face
- Evaluation metrics such as **ROUGE** and **F1 score**
- Optional fine-tuning and saving the model
- Ready-to-run on Google Colab

---
## Installation
```
pip install -r requirements.txt
```
