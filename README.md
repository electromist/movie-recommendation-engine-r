# Movie-Recommendation-Engine-r 🎬

> An end-to-end Machine Learning recommendation system comparing Popularity-Based, Content-Based (TF-IDF & Cosine Similarity), and Machine Learning / Collaborative Filtering algorithms.

## 📌 Overview
**Movie-Recommendation-Engine-r** demonstrates how production recommendation engines are designed and evaluated across different personalization tiers:
1. **Popularity-Based Filtering:** Baseline ranking using weighted rating formulas (IMDb weighted score) to solve the cold-start problem.
2. **Content-Based Filtering:** Metadata feature engineering (genres, keywords, cast, crew), vector space embeddings (TF-IDF), and cosine similarity metrics to recommend relevant titles based on content similarity.
3. **Machine Learning / Collaborative Filtering:** Matrix factorization and predictive modeling on user-item interaction histories to discover latent preference patterns.

## 📁 Repository Structure
```text
├── Content-based.ipynb      # Metadata vectorization, TF-IDF & Cosine Similarity
├── Machine_learning.ipynb   # Matrix factorization & collaborative ML modeling
├── Popularity-based.ipynb   # Baseline popularity-weighted ranking algorithms
├── resources/               # Datasets and metadata assets
├── requirements.txt         # Python dependencies
└── README.md
```

## 🧠 Core ML Techniques
- **Vector Space Modeling:** High-dimensional text representation and n-gram extraction.
- **Cosine Similarity:** Metric computation across sparse feature matrices.
- **Matrix Factorization & Latent Factor Models:** Decomposing user-item rating matrices to uncover latent affinity dimensions.
- **Cold-Start Handling:** Algorithmic fallback strategies for unrated items and new users.

## ⚙️ Setup & Execution

### 1. Installation
```bash
python -m venv venv
# Windows:
.\venv\Scripts\activate
# Linux/macOS:
source venv/bin/activate

pip install -r requirements.txt
```

### 2. Run Notebooks
Launch Jupyter Lab or Notebook:
```bash
jupyter lab
```
Explore the interactive pipelines in `Popularity-based.ipynb`, `Content-based.ipynb`, and `Machine_learning.ipynb`.

## 📄 License
MIT License
