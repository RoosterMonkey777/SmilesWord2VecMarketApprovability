# SmilesWord2VecforMaketApprovability

This project explores the use of Word2Vec-based algorithms on SMILES (Simplified Molecular Input Line Entry System) representations of chemical compounds to predict their market approvability.

We experiment with both Word2Vec models (CBOW and Skip-gram) trained on SMILES sequences and compare their performance with ChemBERTa — a pre-trained Transformer-based model for chemical property prediction.

## Objective
- Learn meaningful embeddings from SMILES strings using Word2Vec (CBOW & Skip-gram).
- Use these embeddings to train a downstream classifier to predict whether a compound is likely to be market-approved.
- Compare performance of our Word2Vec models against ChemBERTa model.

## Requirements
Python 3.9+
pandas
scikit-learn
transformers
torch

## How to Run

### 1. Clone the Repository
git clone https://github.com/RoosterMonkey777/SmilesWord2VecforMaketApprovability.git
cd SmilesWord2VecforMaketApprovability

### 2.Install Dependencies
pip install pandas scikit-learn gensim transformers torch

### 3. Run Notebooks
Open your preferred Jupyter environment

<img width="717" alt="image" src="https://github.com/user-attachments/assets/ab0dee43-d1a9-41ff-a295-b2d8f9e9c492" />
