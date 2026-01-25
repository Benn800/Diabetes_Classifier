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
- **Target Variable:** Diabetes diagnosis (binary)

The dataset is used strictly for academic purposes.

---

## Project Structure
``` text 
faidm-diabetes-project/
│
├── data/
│ ├── raw/ # Original dataset 
│ └── processed/ # Cleaned and preprocessed data
│
├── notebooks/
│ ├── 01_data_understanding.ipynb
│ ├── 02_preprocessing_eda.ipynb
│ ├── 03_clustering.ipynb
│ └── 04_classification.ipynb
│
├── figures/ # Exported plots and evaluation figures
├── README.md
```

Each notebook corresponds to a distinct stage of the data mining lifecycle to ensure clarity, reproducibility, and ease of review.

---

## Methodology Overview

### Data Understanding & Preprocessing
- Exploratory Data Analysis (EDA)
- Handling class imbalance
- Feature scaling and preparation
- Justification of preprocessing decisions

### Clustering (Unsupervised Learning)
- Algorithm: K-Means
- Cluster evaluation using internal metrics (e.g., silhouette score)
- Interpretation of population risk profiles

### Classification (Supervised Learning)
- Primary model: Logistic Regression
- Model evaluation using accuracy, precision, recall, F1-score, and ROC-AUC
- Probability estimation for diabetes risk
- Comparison with alternative models (where applicable)

---

## Tools and Technologies
- **Programming Language:** Python  
- **Libraries:** pandas, numpy, scikit-learn, matplotlib, seaborn  
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
3. Run notebooks sequentially from `01_data_understanding.ipynb` to `04_classification.ipynb`

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
