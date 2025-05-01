# ORION 🛰️ — Asteroid Classification System

**ORION** is an advanced machine learning pipeline designed to classify NASA asteroid data into **NEO (Near Earth Object)**, **PHA (Potentially Hazardous Asteroid)**, and **NHA (Non-Hazardous Asteroid)** categories. Developed for **Yuri Night Planet Hunt (IIT BHU)**, this project earned the **Runner-Up Award** for its innovation, performance, and astrophysics-driven feature engineering.

> 🚀 **Runner-Up | Yuri Night Planet Hunt, IIT BHU (2025)**

---

## ✨ Key Features

- 🛰️ **Astrophysics-Informed Features**  
  Engineered features like **MOID/Semi-Major Axis ratio**, inclination, eccentricity, and other orbital parameters.

- ⚡ **High-Performance Classifiers**  
  Benchmarked ML models — **XGBoost** delivered the highest accuracy.

- 🔍 **Explainable AI**  
  Feature importance plots, ROC curves, and decision boundary visualizations for interpretability.

- 🔗 **Scalable & Modular Pipeline**  
  Easily adaptable for other space datasets and celestial classification tasks.

---

## 🛠️ Tech Stack

| Tool        | Purpose                         |
|-------------|---------------------------------|
| Python 3.x  | Core language                  |
| XGBoost     | Ensemble classifier            |
| Scikit-learn| ML models & preprocessing      |
| Pandas      | Data manipulation              |
| NumPy       | Numerical computing            |
| Matplotlib & Seaborn | Visualization        |

---

## 📂 Repo Structure

```
ORION/
├── data/                # NASA Asteroid Dataset
├── notebooks/           # EDA & Model Training
├── models/              # Trained Models & Metrics
├── utils/               # Helper Scripts
├── figures/             # Plots & Visualizations
├── requirements.txt     # Dependencies
└── README.md
```

---

## ⚡ Quickstart

```bash
# Clone the repository
git clone https://github.com/silverballz/ORION.git
cd ORION

# Install dependencies
pip install -r requirements.txt

# Open the notebook
jupyter notebook notebooks/orion_model.ipynb
```

---

## 📊 Performance Summary

| Model       | Accuracy | ROC AUC | Precision | Recall |
|-------------|----------|---------|-----------|--------|
| **XGBoost** | ~94%     | High    | Excellent | Strong |
| RandomForest| ~91%     | High    | Strong    | Moderate |

> **Top Feature:** MOID/Semi-Major Axis ratio  
> **Best Model:** XGBoost Classifier

---

## 🚧 Future Work

- Integrate **Quantum Machine Learning** models (QSVM, QNN)
- Explore **Unsupervised Clustering** for unknown asteroid types
- Deploy **Streamlit Dashboard** for real-time asteroid classification

---

## 👨‍💻 Contributors

- **Anurag Sharma** — [LinkedIn](https://www.linkedin.com/in/anurag-sharma-362664240/) | [GitHub](https://github.com/silverballz)
- **Nityansh Pant** — Collaborator & Co-Developer

---

## 📜 License

Licensed under the MIT License — see the `LICENSE` file for details.

---

## 🌌 Acknowledgements

- NASA Asteroid Database  
- Yuri Night Planet Hunt (IIT BHU)  
- XGBoost, Scikit-learn, and Open-source Community

---

## 📛 Badges *(Optional — you can add these to your repo once it's public)*

```md
![MIT License](https://img.shields.io/badge/License-MIT-blue.svg)
![Python](https://img.shields.io/badge/Python-3.x-blue)
![Built with XGBoost](https://img.shields.io/badge/Built%20with-XGBoost-orange)
```

---

## 📥 Requirements Template (requirements.txt)

```
xgboost
scikit-learn
numpy
pandas
matplotlib
seaborn
jupyter
```

---

> ⚡ **Pro tip:** Once you push, pin a project screenshot or ROC curve plot in the README for a visual pop!

