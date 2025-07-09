# 🧠 Machine Learning Classification on Custom Dataset

🚀 This project builds and compares multiple machine learning models to classify custom data loaded from `.npy` files. It includes exploratory data analysis (EDA), visualization, model training, and evaluation.

---

## 📂 Dataset
- Stored as NumPy arrays: `X_train`, `X_test`, `y_train`, `y_test`
- Loaded from Google Drive in Google Colab.

---

## 🔍 Workflow Summary
### 1️⃣ Data Loading & Exploration
- Loaded datasets from `.npy` files.
- Checked data shapes, basic statistics, and class distribution.
- Verified absence of missing values.

### 2️⃣ Data Visualization
- Visualized sample signals from each class to understand patterns.
- Used boxplots to compare feature distributions by class.

### 3️⃣ Model Training & Evaluation
- Trained multiple machine learning classifiers that include catboost , xgboost and light gbm
- Evaluated using accuracy and confusion matrix on the test set.

---

## 🛠 Tools & Libraries
| Library         | Purpose                          |
|-----------------|----------------------------------|
| NumPy           | Data loading & manipulation     |
| Matplotlib, Seaborn | Data visualization         |
| scikit-learn    | Machine learning models & metrics |

---

## 🚀 Results
- Compared multiple classifiers to determine the best performing model.
- Analyzed confusion matrices and accuracy scores.

---

## 📌 Next Steps
- Hyperparameter tuning (GridSearchCV / RandomizedSearchCV)
- Try additional classifiers (XGBoost, Gradient Boosting)
- Deploy best model with a simple streamlit or gradio app

---

## 🤝 Let’s Connect
If you found this interesting, please ⭐ the repo or connect on [LinkedIn](https://linkedin.com).

---
