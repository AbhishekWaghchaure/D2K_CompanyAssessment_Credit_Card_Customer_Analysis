# D2K_CompanyAssessment_Credit_Card_Customer_Analysis

📋 Project Overview

This project was completed as part of a pre-assessment task for D2k Technologies. The goal was to predict customer attrition (churn) using a dataset of customer information and interaction metrics. The solution demonstrates a robust machine learning pipeline for identifying at-risk customers, offering actionable insights for retention strategies.


📂 Directory Structure

├── data/                    # Dataset files

├── notebooks/               # Jupyter notebooks for EDA and preprocessing

├── results/                 # Output files and model performance metrics

├── README.md                # Project documentation

└── requirements.txt         # Required Python libraries

🛠️Key Features

	•	Data Preprocessing: Cleaning, feature selection, and encoding categorical variables.
	•	Exploratory Data Analysis (EDA): Gained insights into customer demographics, behavior, and attrition patterns.
	•	Model Selection and Tuning:
		•	Compared multiple machine learning models using cross-validation.
		•	Performed hyperparameter tuning for the best-performing model.
		•	Model Evaluation: Evaluated the final model using metrics like accuracy, precision, recall, and F1-score.

 🚀 Technologies Used

	•	Programming Language: Python
	•	Libraries:
	•	pandas, numpy for data handling
	•	matplotlib, seaborn for visualization
	•	scikit-learn for model training and evaluation

 🧪 Results

	•	Best Model: Random Forest Classifier
	•	Accuracy on Test Set: 96.9%
	•	Key Insights:
	•	Customers with higher transaction counts and active engagement are less likely to churn.
	•	Targeted interventions for customers with low activity can significantly reduce attrition.

# Overview of what is done -

This repository contains the analysis, cleaning, and modeling tasks performed as part of the take-home assessment for D2K Technologies. The tasks are structured as follows:

1. **Data Cleaning and Exploration** (`cleaning_and_analysis.ipynb`)
2. **Classification Modeling** (`model_training_classification.ipynb`)
3. **Segmentation and Clustering** (`model_training_segmentation.ipynb`)

---

## Notebook Summaries

### 1. **Data Cleaning and Exploration**
- **Dataset:** Bank Churners Dataset (10,127 rows, 23 columns)
- **Key Insights:**
  - **Numeric Data:**
    - Average customer age: ~46 years.
    - Most customers have 2–3 dependents and have been with the bank for 36 months on average.
  - **Categorical Data:**
    - Majority of customers are "Existing Customers" (85%).
    - Most customers hold a "Blue" card.
  - **Data Inconsistencies:**
    - Unknown values in `Education_Level`, `Marital_Status`, and `Income_Category`.
    - Skewed distribution in `Card_Category`.

#### Exploratory Data Analysis (EDA)
- **Attrition Overview:**
  - Dataset is imbalanced, with a majority of "Existing Customers."
- **Gender Analysis:**
  - Slightly higher attrition rates for females.
- **Education and Income Levels:**
  - Higher attrition among customers with lower education and income levels.
- **Credit Limit and Utilization:**
  - Attrited customers tend to have lower credit limits and higher utilization ratios.
- **Correlation Analysis:**
  - Strong correlation between `Total_Trans_Ct` and `Total_Trans_Amt`.

---

### 2. **Classification Modeling**
This notebook focused on training and evaluating classification models to predict customer attrition. (Details of models and performance metrics can be found in the notebook.)

---

### 3. **Segmentation and Clustering**
- **Objective:**
  - Group customers into clusters for targeted marketing and service personalization.
- **Clustering Approach:**
  - Features were selected based on domain relevance.
  - Optimal number of clusters determined using the knee method.
- **Results:**
  - Three clusters were identified, each representing a distinct customer segment.

---

## How to Use This Repository
1. Clone the repository:
   ```bash
   git clone <repository_url>
🤝 Acknowledgments

This project was completed as a pre-assessment task for D2k Technologies. Thanks to the organization for providing the opportunity and dataset.
