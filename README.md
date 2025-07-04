
## 🧠 Autism Classification using ML Models

This project focuses on detecting Autism Spectrum Disorder (ASD) using machine learning techniques. It compares multiple models on real-world autism screening data, applies SMOTE for class imbalance, and analyzes bias-variance tradeoffs.

---

### 📁 Repository Structure

```
autism-ml-classification/
│
├── data/
│   └── csv_result-Autism-Adult-Data.csv
│
├── notebooks/
│   └── autism_classification_pipeline.ipynb
│
├── outputs/
│   └── model_comparison_plot.png
│
├── README.md
└── requirements.txt
```

---

## 📊 Models Used

The following models were trained and evaluated:

* ✅ Random Forest Classifier
* ✅ K-Nearest Neighbors (KNN)
* ✅ XGBoost Classifier
* ✅ CatBoost Classifier

---

## ⚙️ Techniques & Tools

| Technique                   | Description                                     |
| --------------------------- | ----------------------------------------------- |
| Label Encoding              | For categorical variables                       |
| SMOTE                       | To balance the imbalanced ASD class             |
| Correlation Heatmap         | For feature selection                           |
| Train-Test Split            | Standard ML workflow                            |
| Cross-validation            | For reliable model accuracy estimates           |
| Bias-Variance Decomposition | Using `mlxtend` to understand model performance |
| ROC-AUC Curves              | To compare classifier performance visually      |
| Matplotlib / Seaborn        | For visualization                               |

---

## 🔬 Results

After SMOTE and feature selection, all models achieved high performance:

| Model         | Accuracy (Post-SMOTE) |
| ------------- | --------------------- |
| Random Forest | ~100%                |
| KNN           | ~99.7%               |
| XGBoost       | ~99.9%               |
| CatBoost      | ~99.8%               |

> 📌 All results include cross-validation and ROC-AUC analysis.

---

## 📈 Visualization

![Model Comparison](outputs/model_comparison_plot.png)

---

## 🚀 How to Run

1. Clone the repo:

```bash
git clone https://github.com/your-username/autism-ml-classification.git
cd autism-ml-classification
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the notebook:

```bash
jupyter notebook notebooks/autism_classification_pipeline.ipynb
```

---

## 📦 Requirements

```
pandas
numpy
scikit-learn
matplotlib
seaborn
xgboost
catboost
imblearn
mlxtend
```

Use the following to generate:

```bash
pip freeze > requirements.txt
```

---

## 📚 Dataset

* Source: [Autism Screening Adult Data](https://www.kaggle.com/datasets/farhanmd29/autism-screening-on-adults)
* Format: CSV
* Attributes: Gender, age, responses to questions (A1 to A10), app usage, etc.

---

## 🤝 Contribution

Feel free to fork the repo and submit pull requests to enhance the model or visualization.

---

## 📬 Contact

**Vivek Harsh**
[🔗 LinkedIn](https://www.linkedin.com/in/vivekharshcodecraft/)
[💻 GitHub](https://github.com/HarshTechStack)
✉️ [vivekharsh.work@gmail.com](mailto:vivekharsh.work@gmail.com)
```
