# 🎬 Recommendation System Regarding IMDb

This repository hosts a **Movie Recommendation System** built to suggest *similar movies* to a given title using data from IMDb.  
It leverages **GPU acceleration** through [RAPIDS cuDF](https://rapids.ai/) and **Nearest Neighbors** algorithms to deliver fast, efficient content-based recommendations.

---

## 🚀 Overview

The system computes similarity between movies based on textual and categorical features such as genres and descriptions.  
Using **cuDF**, large datasets are processed directly on the GPU, drastically improving performance compared to traditional pandas workflows.

---

## 🧠 Key Features

- **GPU-powered data processing** with cuDF (RAPIDS)  
- **NearestNeighbors model** for fast similarity search  
- **Content-based recommendation** using TF-IDF and vector similarity  
- Simple CLI or notebook interface for experimentation  
- Scalable design suitable for production integration

---

## 🛠 Tech Stack

| Component | Purpose |
|------------|----------|
| **Python 3.x** | Programming language |
| **cuDF** | GPU DataFrame library for high-speed data manipulation |
| **scikit-learn / cuML** | NearestNeighbors and ML models |
| **numpy** | Numerical computations |
| **pandas** | Compatibility layer |
| **Jupyter Notebook** | Interactive exploration |

---

## 📦 Installation

Make sure you have an environment with CUDA support.
```bash
git clone https://github.com/kasratookallo-svg/Recommendation_System_Regarding_IMDB.git
cd Recommendation_System_Regarding_IMDB
pip install -r requirements.txt
