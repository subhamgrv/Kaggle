# 🚢 Kaggle Projects

A collection of my Kaggle competition notebooks and machine learning experiments. This repository serves as a personal learning journal documenting my journey through data science challenges.

---

## 📁 Projects

### 1. My First Kaggle → Titanic Survival Prediction

**Notebook:** [`My_First_Kaggle___Titanic.ipynb`](./My_First_Kaggle___Titanic.ipynb)

**Competition:** [Titanic - Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic)

**Status:** 🟡 In Progress

#### Overview
The classic beginner Kaggle challenge — predicting which passengers survived the Titanic shipwreck using machine learning. This notebook covers the full pipeline from data acquisition to model submission.

#### What's Covered
- Setting up the Kaggle API in Google Colab
- Downloading the Titanic competition dataset via the Kaggle CLI
- Initial data exploration setup using `numpy` and `pandas`

#### Dataset
- **Source:** [Kaggle Titanic Competition](https://www.kaggle.com/competitions/titanic/data)
- **Files:**
  - `train.csv` — Training data with survival labels
  - `test.csv` — Test data for predictions
  - `gender_submission.csv` — Sample submission file

#### Tech Stack
| Tool | Purpose |
|------|---------|
| Python 3 | Core language |
| NumPy | Numerical computation |
| Pandas | Data manipulation |
| Google Colab | Notebook environment |
| Kaggle API | Dataset download |

#### Setup (Google Colab)
1. Open the notebook in [Google Colab](https://colab.research.google.com/github/subhamgrv/Kaggle/blob/main/My_First_Kaggle_%3E_Titanic.ipynb)
2. Upload your `kaggle.json` API token when prompted
3. Run all cells sequentially

> **Note:** Your `kaggle.json` file should **never** be committed to this repository. It is your private API key.

---

## 🛠️ Getting Started Locally

### Prerequisites
```bash
pip install kaggle numpy pandas jupyter
```

### Kaggle API Setup
1. Go to [kaggle.com](https://www.kaggle.com) → Account → Create API Token
2. Download `kaggle.json`
3. Place it at `~/.kaggle/kaggle.json`
4. Run: `chmod 600 ~/.kaggle/kaggle.json`

---

## 📌 Repository Structure

```
Kaggle/
├── My_First_Kaggle___Titanic.ipynb   # Titanic competition notebook
└── README.md                          # This file
```

---

## 🎯 Goals

- [ ] Complete Titanic EDA (Exploratory Data Analysis)
- [ ] Feature engineering
- [ ] Train and compare multiple ML models
- [ ] Submit predictions to Kaggle leaderboard
- [ ] Add more Kaggle competition notebooks

---

## 📚 Resources

- [Kaggle Learn](https://www.kaggle.com/learn) — Free ML courses
- [Titanic Competition](https://www.kaggle.com/competitions/titanic) — Official competition page
- [Kaggle API Docs](https://github.com/Kaggle/kaggle-api) — CLI documentation

---

*Last updated: March 2026 | More projects coming soon!*
