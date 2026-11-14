# 🧠 SUPERVISED MACHINE LEARNING
### Advanced Learning & Implementation Repository

<p align="center">
<img src="https://img.shields.io/badge/MACHINE-LEARNING-00D4FF?style=for-the-badge&logo=probot" />
<img src="https://img.shields.io/badge/SUPERVISED-LEARNING-7B61FF?style=for-the-badge&logo=googlescholar" />
<img src="https://img.shields.io/badge/PYTHON-3.x-FFD43B?style=for-the-badge&logo=python&logoColor=black" />
<img src="https://img.shields.io/badge/SCIKIT--LEARN-ML-F7931E?style=for-the-badge&logo=scikitlearn" />
</p>
<p align="center"><b>From Mathematical Foundations to Intelligent Predictive Models.</b></p>
<p align="center">A practical learning environment for supervised learning theory, algorithms, mathematical concepts, and Python implementations.</p>
<p align="center"><a href="https://github.com/abhigyansutar45-code/Supervised-Machine-Learning"><img src="https://img.shields.io/badge/EXPLORE-REPOSITORY-181717?style=for-the-badge&logo=github" /></a> <a href="https://github.com/abhigyansutar45-code/Supervised-Machine-Learning/stargazers"><img src="https://img.shields.io/github/stars/abhigyansutar45-code/Supervised-Machine-Learning?style=for-the-badge&color=yellow" /></a></p>

---

## 📌 TABLE OF CONTENTS
- [01. Introduction](#-01-introduction)
- [02. Supervised Learning](#-02-supervised-learning)
- [03. Learning Architecture](#-03-learning-architecture)
- [04. Learning Types](#-04-learning-types)
- [05. Algorithms](#-05-algorithms)
- [06. Mathematical Foundations](#-06-mathematical-foundations)
- [07. Model Evaluation](#-07-model-evaluation)
- [08. Technology Stack](#-08-technology-stack)
- [09. Repository Structure](#-09-repository-structure)
- [10. Getting Started](#-10-getting-started)
- [11. Learning Roadmap](#-11-learning-roadmap)
- [12. References](#-12-references)
- [13. 3D Arcade Experience](#-13-3d-arcade-experience)
- [14. Author](#-14-author)

## 🔷 01. INTRODUCTION
**Supervised Machine Learning (SML)** is a branch of Artificial Intelligence that enables computers to learn patterns from labeled datasets and make predictions on previously unseen data.

### 🎯 Primary Objectives
- Understand supervised learning principles.
- Explore regression and classification.
- Study mathematical foundations of predictive models.
- Practice data preprocessing and feature engineering.
- Evaluate models using statistical metrics.
- Build practical machine learning implementations with Python.

## 🔬 02. SUPERVISED LEARNING
A supervised learning algorithm learns from labeled examples: input features paired with their correct target values.

$$Y=f(X)+\epsilon$$

| Symbol | Meaning |
|:--:|---|
| X | Input features |
| Y | Target variable |
| f(X) | Learned predictive function |
| ε | Random error or noise |

~~~text
LABELED DATA → PREPROCESSING → FEATURE ENGINEERING
      → TRAIN / TEST SPLIT → MODEL TRAINING
      → EVALUATION → PREDICTION ON NEW DATA
~~~

## ⚙️ 03. LEARNING ARCHITECTURE
| Stage | Process | Purpose |
|:--:|---|---|
| 01 | Data Collection | Obtain relevant datasets |
| 02 | Data Cleaning | Handle missing and inconsistent values |
| 03 | Preprocessing | Transform data into suitable formats |
| 04 | Feature Engineering | Create meaningful input features |
| 05 | Data Splitting | Separate training and testing data |
| 06 | Model Training | Learn patterns |
| 07 | Evaluation | Measure generalization |
| 08 | Optimization | Tune model performance |
| 09 | Prediction | Infer outputs for new observations |

## 📊 04. LEARNING TYPES
### A. Regression
Predicts continuous numerical values: house prices, salary, sales, temperature.

| Algorithm | Purpose |
|---|---|
| Linear / Multiple Linear Regression | Model linear relationships |
| Polynomial Regression | Model nonlinear relationships |
| Ridge / Lasso | Regularization |
| Decision Tree Regression | Tree-based prediction |
| Random Forest Regression | Ensemble regression |
| Support Vector Regression | Margin-based regression |

### B. Classification
Predicts discrete categories: spam detection, churn, image classes, fraud detection.

| Algorithm | Purpose |
|---|---|
| Logistic Regression | Probabilistic classification |
| K-Nearest Neighbors | Instance-based classification |
| Decision Tree | Rule-based classification |
| Random Forest | Ensemble classification |
| Support Vector Machine | Margin-based classification |
| Naive Bayes | Probabilistic classification |
| Gradient Boosting / XGBoost | Boosted decision models |

## 🧮 05. ALGORITHMS
**Linear Regression:** $$y=mx+c$$

**Logistic Regression — Sigmoid:** $$\sigma(z)=\frac{1}{1+e^{-z}}$$

- **Decision Trees:** recursively split data using feature-based criteria.
- **Random Forest:** combines predictions from multiple decision trees.
- **K-Nearest Neighbors:** predicts using nearby training observations.
- **Support Vector Machine:** learns a separating boundary with a large margin.
- **Naive Bayes:** applies Bayes' theorem with conditional independence assumptions.

## 📐 06. MATHEMATICAL FOUNDATIONS
| Concept | Application |
|---|---|
| Linear Algebra | Vectors and matrices |
| Probability | Prediction uncertainty |
| Statistics | Distributions and inference |
| Calculus | Gradients and optimization |
| Information Theory | Entropy and information gain |
| Distance Metrics | Similarity calculations |

**Mean Squared Error:** $$MSE=\frac{1}{n}\sum_{i=1}^{n}(y_i-\hat y_i)^2$$

**Mean Absolute Error:** $$MAE=\frac{1}{n}\sum_{i=1}^{n}|y_i-\hat y_i|$$

**R-squared:** $$R^2=1-\frac{SS_{res}}{SS_{tot}}$$

**Gradient Descent:** $$\theta_{new}=\theta_{old}-\alpha\nabla J(\theta)$$

## 📈 07. MODEL EVALUATION
- **Regression:** MAE, MSE, RMSE, R-squared, Adjusted R-squared.
- **Classification:** Accuracy, Precision, Recall, F1-score, Confusion Matrix, ROC-AUC, Log Loss.

| | Predicted Positive | Predicted Negative |
|---|---:|---:|
| Actual Positive | True Positive | False Negative |
| Actual Negative | False Positive | True Negative |

## 🐍 08. TECHNOLOGY STACK
<p><img src="https://skillicons.dev/icons?i=python,numpy,pandas,sklearn,jupyter,vscode,github" alt="Python data science technology stack" /></p>

| Technology | Purpose |
|---|---|
| Python | Main programming language |
| NumPy | Numerical computing |
| Pandas | Data manipulation |
| Matplotlib / Seaborn | Visualization |
| Scikit-learn | Machine learning |
| Jupyter Notebook | Interactive experimentation |
| VS Code | Development environment |

## 📁 09. REPOSITORY STRUCTURE
~~~text
Supervised-Machine-Learning/
├── .github/workflows/deploy-pages.yml
├── assets/snake-ladder-preview.svg
├── Supervision Machine Learning/
├── supervised-machine-learning.ipynb
├── supervised_machine_learning.ipynb
├── index.html
├── LEARN.md
└── README.md
~~~

| Resource | Description |
|---|---|
| [Notebook 01](supervised-machine-learning.ipynb) | Supervised ML notebook |
| [Notebook 02](supervised_machine_learning.ipynb) | Additional ML notebook |
| [Learning Notes](LEARN.md) | Learning documentation |
| [Learning Folder](Supervision%20Machine%20Learning/) | Additional materials |
| [Play the Game](index.html) | Interactive browser game |

## 🚀 10. GETTING STARTED
~~~bash
git clone https://github.com/abhigyansutar45-code/Supervised-Machine-Learning.git
cd Supervised-Machine-Learning
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
jupyter notebook
~~~
Open either notebook and execute its cells.

## 🗺️ 11. LEARNING ROADMAP
- [x] Introduction to Supervised Machine Learning
- [ ] Regression and Classification
- [ ] Data Preprocessing and Feature Engineering
- [ ] Linear and Logistic Regression
- [ ] Decision Trees and Random Forests
- [ ] Support Vector Machines and KNN
- [ ] Naive Bayes
- [ ] Model Evaluation and Cross-Validation
- [ ] Hyperparameter Optimization
- [ ] End-to-End ML Projects

## 📚 12. REFERENCES
- [Scikit-learn Documentation](https://scikit-learn.org/stable/)
- [Python Documentation](https://docs.python.org/3/)
- [NumPy Documentation](https://numpy.org/doc/)
- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [Matplotlib Documentation](https://matplotlib.org/stable/)
- [Google Machine Learning Education](https://developers.google.com/machine-learning)
- [Kaggle Learn](https://www.kaggle.com/learn)

---

## 🎮 13. 3D ARCADE EXPERIENCE

<p align="center"><img src="assets/snake-ladder-preview.svg" alt="3D-inspired Snake and Ladder arcade preview" width="100%" /></p>
<p align="center"><b>TAKE A BREAK FROM THE ALGORITHMS. ENTER THE ARCADE.</b><br/>A responsive, playable Snake & Ladder game built with HTML, CSS and JavaScript.</p>
<p align="center">
<a href="https://abhigyansutar45-code.github.io/Supervised-Machine-Learning/"><img src="https://img.shields.io/badge/▶%20PLAY%20SNAKE%20%26%20LADDER-00D4FF?style=for-the-badge&logo=googleplay" alt="Play Snake and Ladder" /></a>
<a href="index.html"><img src="https://img.shields.io/badge/VIEW-GAME%20SOURCE-181717?style=for-the-badge&logo=github" alt="View game source" /></a>
</p>

### ✨ GAME FEATURES
| Feature | Description |
|---|---|
| 🎲 Animated Dice | Rolling dice with randomized results |
| 🧑‍🤝‍🧑 Multiplayer | 2–4 local players |
| 🐍 Snakes & 🪜 Ladders | Classic board movement |
| 🏆 Winning Logic | Exact roll required to reach square 100 |
| 📱 Responsive Board | Desktop, tablet and mobile layouts |
| 🎨 Arcade Interface | Dark glass UI and 3D-inspired board |
| ♻️ New Game | Restart and select player count |

### 🚀 ENABLE GITHUB PAGES (ONE-TIME SETUP)
1. Open repository **Settings → Pages**.
2. Under **Build and deployment**, set **Source** to **GitHub Actions**.
3. Open the **Actions** tab and wait for **Deploy Snake & Ladder Game to GitHub Pages** to finish successfully.
4. Launch the game using the Play button above.

> GitHub README files do not execute embedded JavaScript. The README shows the visual preview and links to the separately hosted playable game.

---

## 👨‍💻 14. AUTHOR
<p align="center"><img src="https://img.shields.io/badge/DEVELOPER-ABHIGYAN%20SUTAR-00D4FF?style=for-the-badge" /></p>
<p align="center"><b>ABHIGYAN SUTAR</b><br/>Machine Learning | Python | Data Science | Artificial Intelligence</p>
<p align="center"><a href="https://github.com/abhigyansutar45-code"><img src="https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github" /></a></p>

---
<p align="center"><b>Building Knowledge. Training Models. Exploring Intelligence.</b></p>
<p align="center">⭐ If you find this repository useful, consider giving it a star!</p>
<p align="center"><sub>© 2026 Abhigyan Sutar | Supervised Machine Learning</sub></p>
