# Product Category Classifier

This project builds a machine learning model to classify e-commerce product titles into categories using a subset of the Flipkart product dataset. It demonstrates the use of both classical NLP and deep learning techniques for automated product tagging, relevant to platforms like Meesho and Flipkart.

## Problem Statement

Given a product title (e.g., "Cotton Saree with Blouse Piece"), predict its product category (e.g., "Fashion"). This helps automate catalog tagging and improves search and recommendation systems.

## Dataset

- Source: Flipkart Product Dataset (from Kaggle)
- Fields used: `product_name`, `product_category`
- Sample size: Filtered and cleaned subset with balanced category distribution

## Models

1. **TF-IDF + Logistic Regression**
   - Baseline model with tokenized, vectorized inputs
   - Fast, interpretable, and effective for short product titles

2. **LSTM (TensorFlow + Keras)**
   - Sequential model using word embeddings and LSTM layers
   - Captures context and ordering in product titles

## Evaluation

| Model                      | Accuracy |
|---------------------------|----------|
| TF-IDF + Logistic Regression | ~85%     |
| LSTM (TensorFlow)         | ~88–90%  |

Includes confusion matrix and sample predictions for comparison.

## Tech Stack

- Python
- Scikit-learn, TensorFlow, Keras
- Pandas, NumPy, NLTK
- Google Colab

## Sample Predictions

| Product Title                         | Predicted Category |
|--------------------------------------|---------------------|
| Cotton Saree with Blouse             | Fashion             |
| LED Strip Light for Home Decoration  | Electronics          |
| Stainless Steel Water Bottle         | Home                |

## How to Run

1. Open the Colab Notebook [link here]
2. Run all cells in sequence
3. Upload dataset or use provided one
4. Train and evaluate both models

## Author

Anushka Tiwari  
[LinkedIn](https://www.linkedin.com/in/anushkatiwari07/) • [GitHub](https://github.com/anushka707) • [Email](mailto:anushka.tiwari0709@gmail.com)
