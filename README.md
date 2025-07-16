# Mental Health Data Analysis & Classification

This project analyzes mental health data to identify factors related to depression, anxiety, sleepiness, and BMI. It also includes machine learning models to predict an individual's mental health status based on these factors.

# Objective

- Analyze mental health indicators using Exploratory Data Analysis (EDA)
- Visualize patterns in PHQ, GAD, Epworth Sleepiness, and BMI
- Build classification models to predict psychological risk

#Tools & Libraries

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn (Logistic Regression, Random Forest, SVM, KNN)
- Confusion Matrix & Evaluation Metrics

## Machine Learning Models Compared

| Model               | Accuracy | Precision | Recall | F1-score |
|--------------------|----------|-----------|--------|----------|
| Logistic Regression| 0.987    | 1.000     | 0.952  | 0.976    |
| Random Forest      | 0.987    | 1.000     | 0.952  | 0.976    |
| SVM                | 0.974    | 0.975     | 0.929  | 0.951    |
| KNN                | 0.923    | 0.895     | 0.810  | 0.850    |

**Best models**: Logistic Regression and Random Forest.

## Highlights

- Custom visualizations (pairplots, boxplots, heatmaps)
- Clean and organized notebook
- Custom colormap for confusion matrix
- Real-life context: Health and psychological wellbeing

## How to Run

1. Clone the repo or open the notebook in Google Colab  
2. Make sure to install required libraries (most are standard)
3. Run all cells in order

##  Dataset 

This project uses a mental health dataset containing:

- `phq_score`, `gad_score`, `epworth_score`, `bmi`
- Gender, Age, Sleep, Mental Health labels

  https://www.kaggle.com/datasets/shahzadahmad0402/depression-and-anxiety-data

