# Diabetes Risk Prediction and Population Segmentation  
**FAIDM Individual Coursework – WM9QG-15**

## Project Overview
This project was completed as part of the *Fundamentals of Artificial Intelligence and Data Mining (WM9QG-15)* module. The objective is to apply supervised and unsupervised learning techniques to analyse population-level health data and derive insights relevant to diabetes risk prediction and public health intervention.

The project addresses two core tasks:
1. **Classification** – Predicting whether an individual has been diagnosed with diabetes and estimating the probability of diagnosis.
2. **Clustering** – Identifying meaningful population segments based on health and lifestyle indicators.

The analysis follows best practices in applied data mining and aligns with the CRISP-DM methodology.

---

## Dataset
- **Source:** UCI Machine Learning Repository  
- **Dataset:** CDC Diabetes Health Indicators  
- **Description:** Survey data from over 250,000 adults, including demographic, lifestyle, and health-related variables.  
- **Target Variable:** Diabetes diagnosis (binary & multiclass)

The dataset is used strictly for academic purposes.

---

## Project Structure
``` text 
faidm-diabetes-project/
│
├── data/
│ ├── raw_data/ # Original dataset 
│ └── processed_data/ # Train/val/test split artifacts
│
├── notebooks/
│ ├── 01_data_understanding.ipynb
│ ├── 02_preprocessing.ipynb
│ ├── 03_classification.ipynb
│ └── 04_clustering.ipynb
│
├── README.md
```

Each notebook corresponds to a distinct stage of the data mining lifecycle to ensure clarity, reproducibility, and ease of review.

---

## Methodology Overview

### Data Understanding & Preprocessing
- Exploratory Data Analysis (EDA)
- Data quality checks, feature types, and distribution analysis
- Train/validation/test split creation and persistence

### Clustering (Unsupervised Learning)
- Algorithms: K-Means and Agglomerative Clustering
- PCA for dimensionality reduction and cluster tendency checks
- Cluster evaluation using internal metrics (silhouette)
- Interpretation of population segments

### Classification (Supervised Learning)
- Models: Logistic Regression (binary and multiclass) and LightGBM
- Threshold tuning for target recall with precision-recall analysis
- Evaluation with precision, recall, F1-score, PR-AUC, and confusion matrices
- Model interpretability via coefficients and SHAP

---

## Tools and Technologies
- **Programming Language:** Python  
- **Libraries:** pandas, numpy, scikit-learn, matplotlib, seaborn, lightgbm, shap  
- **Environment:** Jupyter Notebook  
- **Version Control:** Git & GitHub

---

## Version Control Practice
Version control was managed using **Git**, with incremental commits reflecting each major stage of the CRISP-DM process (data understanding, preprocessing, clustering, classification, and evaluation).  
Commit history demonstrates iterative development and professional workflow practices.

---

## How to Run the Project
1. Clone the repository  
2. Ensure required Python libraries are installed  
3. Run notebooks sequentially from `01_data_understanding.ipynb` to `04_clustering.ipynb`

---

## Notebook Guide
- **01_data_understanding.ipynb**: EDA, feature descriptions, data quality checks, and initial insights.
- **02_preprocessing.ipynb**: Create stratified train/val/test splits and save them for reuse.
- **03_classification.ipynb**: Binary and multiclass classification with threshold tuning and evaluation.
- **04_clustering.ipynb**: PCA-based clustering with model selection and internal validation.

---

## Ethical and Practical Considerations
This project acknowledges potential biases in self-reported health data and reflects on ethical considerations such as fairness, interpretability, and the implications of false predictions in healthcare contexts.

---

## Author
**Bennett Varghese**  
MSc Applied Artificial Intelligence  
University of Warwick

---

## Disclaimer
This project is submitted as part of an academic assessment. The results and models are not intended for clinical use or real-world deployment.
