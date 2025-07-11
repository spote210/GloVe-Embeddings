# GloVe-Embeddings
Semantic Projections from GloVe Embeddings: 3D Visualization of Gender, Age, and Royalty Dimensions
 
 ## GloVe Embeddings with Cosine Similarity      
<img width="361" height="254" alt="Screenshot 2025-07-11 at 12 05 38 PM" src="https://github.com/user-attachments/assets/5f84b09a-dfc4-45c4-b12f-de22a9fe3f86" /> <img width="435" height="456" alt="Screenshot 2025-07-11 at 12 04 38 PM" src="https://github.com/user-attachments/assets/f56e0cfc-e392-46ee-bbc3-d95f63502931" />


# Semantic Projections from GloVe Embeddings

This project explores how GloVe word embeddings can be projected onto interpretable semantic axes—specifically **Gender**, **Age**, and **Royalty**—and visualized in a 3D scatter plot.

## 🔍 Objective

To extract meaningful, human-interpretable relationships from pre-trained GloVe word vectors by:
- Defining semantic axes using vector differences (e.g., `woman - man` for gender).
- Projecting word vectors onto these axes using cosine similarity.
- Visualizing the result in a 3D plot for interactive exploration.

## 📁 Files

- `glove_projection_3d.ipynb` – Jupyter notebook with all the code.
- `glove.6B.100d.txt` – Pre-trained GloVe embeddings (you need to download this).
- `README.md` – This file.

## 📌 Dependencies

```bash
pip install numpy pandas matplotlib plotly
