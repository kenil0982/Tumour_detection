# Tumour_detection
# 🧠 Tumor Detection Using Breast Cancer Data (Python)

## 📌 Overview
This project analyzes the Breast Cancer Wisconsin (Diagnostic) dataset to distinguish between **benign** and **malignant** tumors using various cell characteristics. The focus is on deriving insights through data visualization and statistical analysis, helping understand key factors linked to tumor diagnosis.

## 🛠 Tools & Technologies
- **Python**
- **Pandas** and **NumPy** for data handling
- **Matplotlib** and **Seaborn** for visualizations
- **Jupyter Notebook**

## 🗂 Dataset Description
- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic))
- The dataset contains **30 real-valued features** computed from digitized images of fine needle aspirate (FNA) of breast masses.
- **Target column:** `diagnosis` (`M` = malignant, `B` = benign)

### 🔑 Sample Feature Columns:
- `radius_mean`, `texture_mean`, `perimeter_mean`, `area_mean`, `smoothness_mean`
- `compactness_mean`, `concavity_mean`, `concave points_mean`
- `radius_worst`, `texture_worst`, `area_worst`, etc.
- Each "_worst" column represents the worst-case (largest) value recorded for a specific feature.

## 📊 Key Objectives
- Perform exploratory data analysis (EDA) to understand feature distributions
- Identify correlations between features and tumor types
- Visualize data using plots like heatmaps, histograms, and scatter plots
- (Optional) Use this insight for future ML classification


## 🔍 Key Insights
- Malignant tumors typically have higher `radius_mean`, `perimeter_mean`, and `concavity_worst`
- Strong correlations observed among size-related features (`radius`, `perimeter`, `area`)
- Heatmap and pair plots helped visually separate benign and malignant classes

## 📈 Visuals Used
- Countplot of tumor diagnoses (Benign vs Malignant)
- Boxplots for comparing feature distributions across diagnoses
- Correlation heatmap of all 30 features

## ✅ Future Improvements
- Add a machine learning classifier (e.g., logistic regression, SVM)
- Evaluate using accuracy, confusion matrix, ROC-AUC
- Build a simple Streamlit web app for tumor prediction (optional)



*Disclaimer: This project is for educational purposes only and not intended for real-world medical diagnosis.*

