# causal-sentiment-classification
Discovering Causal Relationships in Noisy Web Data for Sentiment Classification Using Attention Mechanisms

# Discovering Causal Relationships in Noisy Web Data for Sentiment Classification Using Attention Mechanisms

## Overview
This project implements a novel deep learning approach for discovering causal relationships in noisy web data using attention-enhanced architectures. The model is validated on the Sentiment140 dataset and achieves superior performance in sentiment classification.

## Features
- Bidirectional LSTM with attention mechanisms
- Embedding layer for text representation
- Global Average Pooling and Dropout techniques
- Binary classification using sigmoid activation
- Ablation study on key components such as LSTM, attention, and pooling methods

## Results
- Test accuracy: **82.36%**
- F1-Score: **0.8246**
- Outperforms traditional models like Logistic Regression, SVM, and Random Forest.

## Data
The model is trained and validated on the [Sentiment140 dataset](https://www.tensorflow.org/datasets/catalog/sentiment140?hl=fr).

## Model Architecture
The model leverages:
- Embedding layer for word representation
- Bidirectional LSTM for handling sequential data
- Attention mechanisms for dynamically focusing on key parts of the text
- Dense layer with sigmoid activation for binary classification

## How to Run the Code
1. Clone the repository:
   ```bash
   git clone https://github.com/Milouden/causal-sentiment-classification.git






## Citation
Please cite the following paper if you use this code in your work:

```bibtex
@article{Milouden2024,
  title={Discovering Causal Relationships in Noisy Web Data for Sentiment Classification Using Attention Mechanisms},
  author={Your Name},
  journal={Journal Name},
  year={2024},
  volume={XX},
  pages={XX-XX}
}
