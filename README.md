# Exploring Finetuning vs Feature-Based Transfer Learning for IMDb Sentiment Classification

This project investigates two approaches for text classification using DistilBERT:
1. **Fine-tuning** the full model on the IMDb dataset.
2. **Freezing DistilBERT** and training a logistic regression classifier on its embeddings.

## Structure

- `fine_tuning_imdb.py`: Full implementation of both training approaches.
- IMDb dataset: Automatically loaded using Hugging Face Datasets.
- Models: `distilbert-base-uncased` from Hugging Face Transformers.

## Results

| Method                      | Accuracy | F1     |
|----------------------------|----------|--------|
| Fine-Tuned DistilBERT      | 89.2%    | 0.892  |
| Logistic Regression (frozen) | 85.8%  | 0.858  |

## Authors
- Takoudjou Nde Kenneth
- Shakhzodbek Bakhtiyorov

Department of Computer Science, University of Antwerp
