# Breast-Cancer-Diagnostic-System

A Machine Learning project that predicts whether a breast tumor is **Benign** or **Malignant** using the **Wisconsin Breast Cancer Dataset**. The project performs complete data analysis, preprocessing, model comparison, hyperparameter tuning, and model deployment by saving the best-performing model.

---

## 📌 Project Overview

Early detection of breast cancer significantly improves treatment outcomes. This project applies various Machine Learning algorithms to classify tumors based on medical measurements extracted from digitized images of breast masses.

The notebook includes:

- Exploratory Data Analysis (EDA)
- Data Preprocessing
- Feature Scaling
- Training Multiple ML Models
- Model Evaluation
- Hyperparameter Tuning
- Best Model Selection
- Model Saving
- Sample Prediction
- Performance Visualization

---

## 📂 Project Structure

```
Breast-Cancer-Diagnostic/
│
├── Breast_Cancer_Diagnostic.ipynb    # Complete notebook
├── best_model.pkl                    # Saved trained model (generated)
├── scaler.pkl                        # Saved StandardScaler (generated)
├── README.md
```

---

## 📊 Dataset

The project uses the **Wisconsin Breast Cancer Diagnostic Dataset** available in **scikit-learn**.

Dataset Information:

- **Total Samples:** 569
- **Features:** 30
- **Target Classes:**
  - Malignant (Cancerous)
  - Benign (Non-cancerous)

No external dataset download is required.

Dataset is loaded using:

```python
from sklearn.datasets import load_breast_cancer
```

---

## ✨ Features

- Missing value analysis
- Duplicate value detection
- Class distribution visualization
- Statistical summary
- Correlation heatmap
- Histograms
- Boxplots
- Pairplots
- Feature scaling using StandardScaler
- Comparison of multiple ML algorithms
- Hyperparameter tuning using GridSearchCV
- Automatic best model selection
- Model serialization using Joblib
- Sample prediction function
- Confusion Matrix
- ROC Curve
- Feature Importance visualization

---

## 🛠️ Machine Learning Models

The notebook compares several classification algorithms, including:

- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Naive Bayes

The best-performing model is selected based on:

1. Recall
2. ROC-AUC Score
3. F1 Score

---

## 📈 Evaluation Metrics

Each model is evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score

Visualizations include:

- Model comparison chart
- Confusion Matrix
- ROC Curve
- Feature Importance

---

## ⚙️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

---

## 📦 Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Breast-Cancer-Diagnostic.git
```

Move into the project

```bash
cd Breast-Cancer-Diagnostic
```

Install dependencies

```bash
pip install -r requirements.txt
```

or

```bash
pip install numpy pandas matplotlib seaborn scikit-learn joblib
```

---

## ▶️ Running the Project

Launch Jupyter Notebook

```bash
jupyter notebook
```

Open

```
Breast_Cancer_Diagnostic.ipynb
```

Run all cells sequentially.

---

## 💾 Model Saving

The final trained model is saved as:

```
best_model.pkl
```

The fitted scaler is saved as:

```
scaler.pkl
```

These files can be directly used for deployment or integration into a web application.

---

## 🔮 Sample Prediction

The notebook includes a prediction function that:

- Accepts patient feature values
- Applies feature scaling
- Predicts whether the tumor is:
  - **Benign**
  - **Malignant**

---

## 📊 Project Workflow

```
Load Dataset
      │
      ▼
Data Exploration
      │
      ▼
Data Cleaning
      │
      ▼
Train-Test Split
      │
      ▼
Feature Scaling
      │
      ▼
Train Multiple Models
      │
      ▼
Evaluate Performance
      │
      ▼
Hyperparameter Tuning
      │
      ▼
Select Best Model
      │
      ▼
Save Model
      │
      ▼
Predict New Cases
```

---

## 🎯 Learning Outcomes

This project demonstrates:

- End-to-end Machine Learning workflow
- Data preprocessing techniques
- Exploratory Data Analysis
- Classification algorithms
- Hyperparameter optimization
- Model evaluation
- Model persistence using Joblib

---

## 🚀 Future Improvements

- Build a Flask/Django web application
- Deploy on Render or Railway
- Add SHAP explainability
- Create REST API
- Dockerize the project
- Integrate with Streamlit for interactive predictions

### Intern_ID: CITS5093
