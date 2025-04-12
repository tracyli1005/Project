# Content Recommendation System for IBM Watson  
&zwnj;**A Hybrid Recommendation Framework leveraging EDA, Collaborative Filtering, and Matrix Factorization**&zwnj;  

[![Python 3.8+](https://img.shields.io/badge/Python-3.8%2B-blue.svg)]() 
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

This project implements a robust content recommendation system tailored for IBM Watson-based platforms, combining multiple algorithmic approaches to deliver personalized and scalable recommendations.

## 🚀 Features
- &zwnj;**Multi-algorithm Hybrid**&zwnj;: Integrates ranking-based, collaborative filtering, content-based, and matrix decomposition methods.
- &zwnj;**Scalable Architecture**&zwnj;: Designed for deployment on cloud platforms supporting Watson services.

## 🔍 Key Components
### 1. Exploratory Data Analysis (EDA)
- Analyzed user-item interaction patterns using `Pandas` and `Seaborn`.
- Visualized metadata distributions and interaction sparsity matrices.

### 2. Rank-Based Recommendations
- &zwnj;**Method**&zwnj;: Popularity ranking
- &zwnj;**Output**&zwnj;: Top-10 trending items list.

### 3. User-User Collaborative Filtering
- &zwnj;**Similarity Metric**&zwnj;: Cosine/Jaccard similarity.
- &zwnj;**Optimization**&zwnj;: KNN-based neighborhood search with `scikit-learn`.

### 4. Content-Based Filtering
- &zwnj;**Feature Extraction**&zwnj;: IBM Watson NLP for keyword/topic extraction.
- &zwnj;**Matching Engine**&zwnj;: TF-IDF vectorization + cosine similarity.

### 5. Matrix Factorization
- &zwnj;**Algorithms**&zwnj;: 
  - Singular Value Decomposition (SVD) 
- &zwnj;**Performance**&zwnj;: Achieved &zwnj;**RMSE 0.89**&zwnj; on test dataset.

This project implements a robust content recommendation system tailored for IBM Watson-based platforms, combining multiple algorithmic approaches to deliver personalized and scalable recommendations.
### Contributing
Open to collaborations! Fork the repo and submit PRs for enhancements or optimizations.

### Contact
For questions or feedback, reach out at [cli124@hawk.iit.edu].
