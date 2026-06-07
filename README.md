<div align="center">

# 🤖 AI Project — Machine Learning & Data Science

A comprehensive, hands-on educational repository covering the full Data Science & Machine Learning pipeline — from NumPy fundamentals to Convolutional Neural Networks and real-world projects.

> 🌐 **زبان فارسی:** برای خواندن این مستند به زبان فارسی، فایل [`README.fa.md`](./README.fa.md) را ببینید.
> **Persian/Farsi version:** See [`README.fa.md`](./README.fa.md).

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter&logoColor=white)](https://jupyter.org/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=white)](https://www.tensorflow.org/)
[![Keras](https://img.shields.io/badge/Keras-D00000?logo=keras&logoColor=white)](https://keras.io/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](#-license)
[![Stars](https://img.shields.io/github/stars/TahaT80/AI?style=social)](https://github.com/TahaT80/AI/stargazers)
[![Forks](https://img.shields.io/github/forks/TahaT80/AI?style=social)](https://github.com/TahaT80/AI/network/members)

> *"The goal of this repository is to provide a structured, end-to-end learning path for anyone who wants to master Data Science and Machine Learning through practical, reproducible examples."*

</div>

---

## 📑 Table of Contents
- [✨ Overview](#-overview)
- [🎯 Features](#-features)
- [🗂️ Repository Structure](#-repository-structure)
- [📚 Curriculum Roadmap](#-curriculum-roadmap)
- [💻 Tech Stack](#-tech-stack)
- [📊 Datasets](#-datasets)
- [⚙️ Installation](#-installation)
- [🚀 Usage](#-usage)
- [🤝 Contributing](#-contributing)
- [📜 License](#-license)
- [📬 Contact](#-contact)
- [⭐ Show Your Support](#-show-your-support)
- [🙏 Acknowledgments](#-acknowledgments)

---

## ✨ Overview

This repository is a **complete educational track** for Artificial Intelligence, Data Science, and Machine Learning. Each section is self-contained, progressively builds on the previous one, and is packed with commented Jupyter notebooks, real datasets, and end-to-end mini-projects.

Whether you are a beginner learning NumPy arrays or an advanced practitioner training a Convolutional Neural Network on CAPTCHA images, you will find a notebook for your level.

---

## 🎯 Features

- ✅ **Step-by-step Jupyter notebooks** — heavily commented, beginner-friendly.
- ✅ **Real datasets** — Boston Housing, Iris, Diabetes, Titanic-style, Weather, Crypto prices, and more.
- ✅ **End-to-end pipeline** — preprocessing → modeling → evaluation → deployment (Dash).
- ✅ **Classical ML + Deep Learning** — scikit-learn alongside TensorFlow/Keras.
- ✅ **Statistics covered properly** — descriptive & inferential tests (t-test, z-test, chi², ANOVA, A/B testing, normality checks).
- ✅ **15+ mini-projects** — including live crypto price streaming (Nobitex), weather prediction, and CAPTCHA recognition.
- ✅ **Interactive visualization** — Matplotlib, Seaborn, Plotly, and a Dash web app.

---

## 🗂️ Repository Structure

```
AI/
├── part0_datascience/        # Introduction to Data Science
├── part1_numpy/              # NumPy fundamentals
├── part2_pandas/             # Pandas & data wrangling
├── part3_EDA/                # Exploratory Data Analysis
│   ├── part1_Statistics/     # Descriptive & Inferential statistics
│   └── part2_Visualization/  # Matplotlib, Plotly, Dash
├── part4_Machine Learning/   # Core Machine Learning
│   ├── 1_Process/            # Preprocessing, cost functions, regularization, evaluation
│   ├── 2_Supervision/        # Supervised algorithms
│   ├── 3_Unsupervised/       # Unsupervised algorithms
│   └── 4_Noron/              # Neural Networks (Perceptron, CNN)
├── part7_project/            # Real-world mini-projects
└── README.md
```

---

## 📚 Curriculum Roadmap

### 🟢 0️⃣ `part0_datascience` — Introduction
- What is Data Science? Workflow, roles, and tools.

### 🟢 1️⃣ `part1_numpy` — Numerical Computing
- Arrays, broadcasting, indexing, slicing, vectorized operations.
- Linear algebra basics, random numbers, statistics.

### 🟢 2️⃣ `part2_pandas` — Data Manipulation
- `Series` & `DataFrame` essentials.
- Reading/writing CSV, Excel, JSON.
- Merging, joining, pivoting, group-by, and time-series handling.

### 🟡 3️⃣ `part3_EDA` — Exploratory Data Analysis
#### 📈 Statistics
- **Descriptive:** moments, correlation, distribution comparison.
- **Inferential:** A/B Testing, T-Test, Z-Test, Mann-Whitney U Test, Chi-Square, Normality tests, ANOVA.

#### 🎨 Visualization
- **Matplotlib & Seaborn:** static plots for EDA.
- **Plotly:** interactive charts.
- **Dash:** building an analytical web app (`dash_full_app.py`).

### 🟠 4️⃣ `part4_Machine Learning` — Core ML
#### 🔧 `1_Process` — ML Pipeline
- Data preprocessing & feature engineering.
- Cost functions, gradient descent intuition.
- Polynomial, **Ridge**, and **Lasso** regression.
- Classification report (precision, recall, F1).
- Cross-validation and **GridSearchCV**.

#### 👨‍🏫 `2_Supervision` — Supervised Learning
| Algorithm | Notebook |
|-----------|----------|
| Linear Regression | `2_1` → `2_4` |
| Logistic Regression | `3_1` → `3_3` |
| K-Nearest Neighbors | `4_1`, `4_2` (imputation) |
| Decision Tree | `5_2` |
| Random Forest | `5_1`, `5_3` |
| Support Vector Machine | `6_1` |
| Artificial Neural Network | `7_1` |
| Naive Bayes | `8_1` |

#### 🔍 `3_Unsupervised` — Unsupervised Learning
- **K-Means** clustering (with elbow method).
- **PCA** — dimensionality reduction.

#### 🧠 `4_Noron` — Neural Networks & Deep Learning
- **Perceptron** — from-scratch and Keras implementations, saved `.h5` / `.keras` models.
- **Convolutional Neural Networks (CNN)** — CAPTCHA recognition with a custom dataset, encoder, and trained models.

### 🔴 5️⃣ `part7_project` — Real-World Projects

| # | Project | Domain |
|---|---------|--------|
| 1 | Data Science workflow recap | E2E pipeline |
| 2 | Exploratory project | Analysis |
| 3 | Modeling project | ML |
| 4 | **Nobitex live crypto price** (`project_4_nobitex.ipynb`) | Finance / Streaming |
| 5 | **Weather prediction** (`weather.csv`, `weather.ipynb`) | Time-series |
| 6 | **Diabetes classification** | Healthcare |
| 7 | **Price prediction** (`prices.csv`) | Regression |
| 8, 8.5 | Model comparison | ML |
| 9 | Advanced modeling | ML |
| 10 | Capstone-style project | ML |
| 11, 12 | Deep-dive projects | ML |
| 13 | **Image project (CNN)** (`8865148.jpg`, `model_13.keras`) | Computer Vision |
| 14 | **Multi-model project** (4 sub-notebooks, `model_0..3.h5`) | Deep Learning |
| 15 | **Final capstone** (`project_15.ipynb`) | Full pipeline |

---

## 💻 Tech Stack

| Category | Tools |
|----------|-------|
| **Language** | Python 3.8+ |
| **Core** | NumPy, Pandas |
| **Visualization** | Matplotlib, Seaborn, Plotly, Dash |
| **Classical ML** | scikit-learn |
| **Deep Learning** | TensorFlow, Keras |
| **Statistics** | SciPy |
| **Notebooks** | Jupyter / VS Code |

---

## 📊 Datasets

This repository ships with curated sample datasets:

- 🍷 `Advertising.csv` — ad spend vs. sales regression
- 🏠 `BostonHousing.csv` — house price prediction
- 🏥 `breastcancer_training.csv` — cancer classification
- 🩺 `diabetes.csv` — diabetes prediction (used in multiple projects)
- 🌸 `Iris.csv` — classic multi-class classification
- 💼 `Social_Network_Ads.csv` — user behavior classification
- 🏘️ `property data.csv` — real estate preprocessing
- ⚽ `soccer.csv` — sports analytics
- 🌦️ `weather.csv` — time-series forecasting
- 💰 `prices.csv` — financial data

---

## ⚙️ Installation

### 1️⃣ Prerequisites
- **Python 3.8+** — [Download](https://www.python.org/downloads/)
- **Git** — [Download](https://git-scm.com/)
- (Optional) **VS Code** with the *Jupyter* extension.

### 2️⃣ Clone the Repository
```bash
git clone https://github.com/TahaT80/AI.git
cd AI
```

### 3️⃣ Create a Virtual Environment

**Windows (PowerShell):**
```powershell
python -m venv venv
.\venv\Scripts\Activate.ps1
```

**Linux / macOS:**
```bash
python -m venv venv
source venv/bin/activate
```

### 4️⃣ Install Dependencies
```bash
pip install --upgrade pip
pip install numpy pandas matplotlib seaborn scikit-learn scipy plotly dash tensorflow jupyter
```

> 💡 **Tip:** If you only need the classical-ML parts, you can skip TensorFlow:
> `pip install numpy pandas matplotlib seaborn scikit-learn scipy plotly dash jupyter`

---

## 🚀 Usage

### Option A — Jupyter Notebook
```bash
jupyter notebook
```
Then navigate to any folder (`part1_numpy`, `part2_pandas`, …) and open the notebooks.

### Option B — VS Code
Open the project folder in VS Code and open any `.ipynb` file. Select the `venv` kernel when prompted.

### Option C — Run the Dash App
```bash
cd "part3_EDA/part2_Visualization/part2_matplotlib"
python dash_full_app.py
```

### Option D — Live Crypto Stream
```bash
jupyter notebook part7_project/project_4_nobitex.ipynb
# Run all cells — fetches live USDT/IRT price from Nobitex
```

---

## 🤝 Contributing

Contributions are **very welcome** — bug fixes, new notebooks, better explanations, or fresh datasets.

1. 🍴 **Fork** the repository.
2. 🌿 Create a feature branch: `git checkout -b feature/amazing-notebook`
3. ✅ Make your changes and **test** them end-to-end.
4. 📝 Follow **PEP 8** and add comments/markdown to explain your code.
5. 💬 Commit: `git commit -m "Add K-Means elbow-method notebook"`
6. 📤 Push: `git push origin feature/amazing-notebook`
7. 🔁 Open a **Pull Request** describing what you added and why.

---

## 📜 License

This project is released under the **MIT License** — see the `LICENSE` file for details.  
You are free to use, modify, and distribute the code, provided that the original copyright notice is preserved.

> If you fork or reuse significant portions of this work, a credit or a link back to this repository is greatly appreciated. 💙

---

## 📬 Contact

**Taha Tandashtiaran**  
- 📧 Email: [1380.tadas@gmail.com](mailto:1380.tadas@gmail.com)
- 🐙 GitHub: [@TahaT80](https://github.com/TahaT80)

Feel free to reach out for **questions, suggestions, collaboration, or bug reports**.

---

## ⭐ Show Your Support

If this repository helped you learn something new, please consider:

- ⭐ **Starring** the repo
- 🍴 **Forking** it
- 🐦 Sharing it with friends
- 🐛 Opening an **issue** for any bug or improvement idea

Your support keeps the project alive and motivates further contributions! 🚀

---

## 🙏 Acknowledgments

- The **scikit-learn**, **TensorFlow**, **Pandas**, and **NumPy** communities for outstanding open-source tools.
- The **Plotly & Dash** teams for making data visualization delightful.
- All **contributors** and learners who use, improve, and share this material.
- Everyone who taught me — this repo is a tribute to the open-source spirit. 💙

---

<div align="center">
Made with ❤️ and lots of ☕ by <a href="https://github.com/TahaT80">TahaT80</a>
</div>
