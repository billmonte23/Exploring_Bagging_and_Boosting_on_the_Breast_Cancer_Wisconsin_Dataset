# Exploring Bagging and Boosting on the Breast Cancer Wisconsin Dataset

This repository contains the code and report for the tutorial **“Exploring Bagging and Boosting on the Breast Cancer Wisconsin Dataset.”**  
The tutorial compares a single decision tree, Random Forest (bagging), and Gradient Boosting (boosting) on a real medical classification problem.

---

## 📁 Repository Structure

- **Exploring Bagging and Boosting.pdf**  
  Final tutorial report explaining the dataset, methods, results, ethical issues, and accessibility choices.

- **Ensemble Learning Tutorial: Bagging vs Boosting.ipynb**  
  Reproducible Jupyter notebook containing all code to load the data, train models, and generate the figures shown in the report.

- **LICENSE**  
  MIT License specifying reuse permissions.

---

## 📊 Dataset

The project uses the **Breast Cancer Wisconsin (Diagnostic)** dataset via  
`sklearn.datasets.load_breast_cancer`.

- Binary classification: *malignant* vs *benign*  
- 30 numeric input features  
- Loaded directly from scikit-learn — **no manual download required**

---

## 🛠️ Installation and Setup

### 1. Clone the repository

```bash
https://github.com/billmonte23/Exploring_Bagging_and_Boosting_on_the_Breast_Cancer_Wisconsin_Dataset.git
```

### 2. (Recommended) Create & activate a virtual environment

```bash
python -m venv .venv
source .venv/bin/activate     # Windows: .venv\Scripts\activate
```

### 3. Install dependencies

The project requires Python 3.x and common ML libraries:

- numpy  
- pandas  
- matplotlib  
- seaborn  
- scikit-learn  

---

## ▶️ How to Run the Notebook

Launch Jupyter:

```bash
jupyter notebook
```

Open **Ensemble Learning Tutorial: Bagging vs Boosting.ipynb**.

Running the notebook will:

- Load and explore the Breast Cancer dataset  
- Split data into train, validation, and test sets  
- Train:
  - Decision Tree (baseline)
  - Random Forest (bagging)
  - Gradient Boosting (boosting)
- Generate:
  - Accuracy scores  
  - Confusion matrices  
  - Classification reports  
  - Feature importances  
  - Validation curves

All figures in the PDF report are produced automatically.

---

## ♿ Accessibility Notes

Steps taken to ensure accessibility:

- High-contrast, colour-blind-friendly plot styles  
- Alt text added for all figures  
- Clear markdown headings + simple language explanations  
- A Report writing 

---

## 🎯 Intended Learning Outcomes

By following this tutorial, learners will be able to:

- Explain bagging vs boosting and when each is useful  
- Implement Decision Trees, Random Forests, and Gradient Boosting in scikit-learn  
- Interpret confusion matrices, classification reports, and feature importances  
- Understand ethical issues such as false negatives in cancer diagnosis  
- Adapt this workflow to new datasets  

---

## 📜 Licence

This project is released under the **MIT License**.  
See the **LICENSE** file for full details.

A permissive licence ensures others may use this project for learning and teaching with proper attribution.
