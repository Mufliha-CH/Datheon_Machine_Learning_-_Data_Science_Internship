# Datheon — Machine Learning & Data Science Internship

A portfolio of machine learning and data science projects developed as part of the Datheon internship program.

This repository documents practical implementations of machine learning workflows, including exploratory data analysis, data preprocessing, model development, performance evaluation, and result interpretation.

## Project 1: Iris Multi-Class Classification

### Overview

The objective of this project is to build and evaluate machine learning models that classify Iris flowers into their respective species based on their numerical measurements.

### Objectives

- Explore and understand the Iris dataset.
- Perform exploratory data analysis (EDA).
- Prepare features and target labels for model training.
- Build reusable machine learning pipelines.
- Train and compare classification algorithms.
- Evaluate model performance using standard classification metrics.

### Machine Learning Models

**1. Logistic Regression**

A supervised classification algorithm used to predict the species of an Iris flower based on its input features.

**2. Decision Tree Classifier**

A supervised learning algorithm that makes predictions using a sequence of feature-based decision rules.

### Workflow

1. Load and inspect the dataset.
2. Perform exploratory data analysis and visualize feature relationships.
3. Separate input features and target labels.
4. Split the data into training and testing sets using stratified sampling.
5. Standardize features where appropriate.
6. Build and train machine learning pipelines.
7. Generate predictions on the test dataset.
8. Evaluate and compare model performance.

### Model Performance

Both models achieved the following results in the current experiment:

| Evaluation Metric | Logistic Regression | Decision Tree |
|---|---:|---:|
| Accuracy | 93.33% | 93.33% |
| Weighted Precision | 93.33% | 93.33% |
| Weighted Recall | 93.33% | 93.33% |
| Weighted F1-score | 93.33% | 93.33% |

*These results are based on the current train-test split. Performance may vary with different data splits or model configurations.*

### Technology Stack

- **Programming Language:** Python
- **Data Manipulation:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn
- **Development Environment:** Jupyter Notebook
- **Version Control:** Git and GitHub

### Repository Structure

```text
Datheon_Machine_Learning_&_Data_Science_Internship/
│
├── iris.ipynb
└── README.md
```

### Getting Started

#### Prerequisites

- Python 3.9 or later
- Jupyter Notebook or JupyterLab

#### Installation

**1. Clone the repository**

Replace the placeholder with your actual public repository URL.

```bash
git clone <YOUR_PUBLIC_REPOSITORY_URL>
```

**2. Navigate to the project directory**

```bash
cd Datheon_Machine_Learning_&_Data_Science_Internship
```

**3. Install the required libraries**

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

**4. Launch Jupyter Notebook**

```bash
jupyter notebook
```

Open `iris.ipynb` and run the cells in order.

### Evaluation Metrics

The models are evaluated using the following metrics:

- **Accuracy:** Measures the proportion of correctly classified test samples.
- **Precision:** Measures how often a model's class predictions are correct.
- **Recall:** Measures the proportion of actual samples correctly identified.
- **F1-score:** Combines precision and recall using their harmonic mean.
- **Confusion Matrix:** Shows correct and incorrect predictions for each class.

Weighted averages account for the number of samples belonging to each class.

### Key Learnings

- Understanding supervised multi-class classification.
- Performing exploratory data analysis.
- Preparing training and testing datasets.
- Applying feature scaling through machine learning pipelines.
- Training and comparing classification models.
- Evaluating predictive performance using multiple metrics.
- Documenting machine learning experiments for reproducibility.

### Future Enhancements

- Add additional machine learning and data science projects.
- Experiment with more classification algorithms.
- Apply cross-validation and hyperparameter tuning.
- Improve model comparison and experiment documentation.

## Author

Machine Learning & Data Science Internship Participant

*Developed for educational and portfolio purposes as part of the Datheon internship program.*
