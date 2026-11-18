# My_FRIST_AI_PROJ.
Heart Disease Prediction using Machine Learning and Random Forest Classifier. Includes data preprocessing, model training, 10-fold cross-validation, performance evaluation, and feature importance analysis using Python and Scikit-learn.

# ❤️ Heart Disease Prediction using Random Forest

## 📌 Project Overview

This project focuses on predicting the presence of heart disease using Machine Learning techniques, specifically the **Random Forest Classifier**.

The model analyzes clinical patient data containing 13 medical features to classify whether a patient has heart disease or not.

This project was implemented using Python and Scikit-learn, based on a research paper published in 2025.

## 🎯 Project Objectives

- Build a Machine Learning model for heart disease prediction.
- Explore and preprocess clinical datasets.
- Implement a Random Forest classification algorithm.
- Evaluate model performance using different evaluation metrics.
- Analyze feature importance and visualize prediction results.
- Compare the implementation results with published research findings.

## 📊 Dataset

The project uses the **Cleveland Heart Disease Dataset**.

- Number of patients: 303
- Input features: 13
- Target variable: Binary classification
  - `0`: No Heart Disease
  - `1`: Heart Disease

### Features

The dataset includes clinical measurements such as:

- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Resting ECG
- Maximum Heart Rate
- Exercise-Induced Angina
- ST Depression (Oldpeak)
- ST Segment Slope
- Number of Major Vessels
- Thalassemia

## ⚙️ Technologies & Libraries

- Python
- Google Colab
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## 🔬 Methodology

### 1. Data Preprocessing
- Data inspection and statistical analysis.
- Missing value detection and handling.
- Duplicate detection and removal.
- Binary target encoding.
- Outlier detection using the IQR method.
- Class balancing using sample weights.

### 2. Model Implementation

A Random Forest Classifier was implemented using:

- Number of estimators: 100 trees.
- Stratified 10-Fold Cross-Validation.
- 80/20 Train-Test Split.
- Balanced sample weights.

### 3. Model Evaluation

The model was evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC-AUC
- Matthews Correlation Coefficient (MCC)
- Cohen's Kappa
- MAE and RMSE

### 4. Visualization

The project includes:
- Target distribution visualization.
- Feature correlation heatmap.
- Confusion matrix.
- ROC curve.
- Feature importance chart.
- Decision tree visualization.

## 📈 Results

The Random Forest model achieved the following results:

| Evaluation Metric | Result |
|---|---:|
| Accuracy (10-Fold CV) | 83.17% |
| Mean Accuracy (10 Seeds) | 82.81% |
| ROC-AUC | 0.900 |
| Precision | 0.832 |
| Recall | 0.832 |
| F1-Score | 0.831 |

The model also demonstrated relatively stable performance across 10 different random seeds.

### Most Important Features

The most influential features identified by the model were:

1. Chest Pain Type (`cp`)
2. Thalassemia (`thal`)
3. Number of Major Vessels (`ca`)
4. Maximum Heart Rate (`thalach`)

## 📚 Research Reference

This project is based on the following research paper:

N. Bhadu and J. Singh, "Performance Analysis and Comparison of Machine Learning Algorithms for Predicting Heart Disease," *IAES International Journal of Artificial Intelligence*, vol. 14, no. 4, pp. 2849–2863, August 2025.

DOI: https://doi.org/10.11591/ijai.v14.i4.pp2849-2863

## 🚀 How to Run

1. Clone this repository:

   ```bash
   git clone YOUR_REPOSITORY_URL
   ```

2. Open the Jupyter Notebook:

   `heart_disease_random_forest V1.ipynb`

3. Install the required libraries if needed:

   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn
   ```

4. Run the notebook cells.

5. Upload the Cleveland dataset CSV or ZIP file when prompted.

6. Review the model evaluation results and visualizations.

**Note:** The notebook is designed to work with Google Colab and also supports local execution when the dataset is available in the working directory.

## ⚠️ Disclaimer

This project is developed for educational and research purposes only. It is not intended to replace professional medical diagnosis or clinical decision-making.

## 👨‍💻 Author

**Shehab Eldin Khalied Mohamed**

Biomedical Engineering Student

Machine Learning | Medical Engineering | Biomedical Applications
