# Multi-Class Benchmark Classification Pipeline

**Internship:** Datheon – Machine Learning & Data Science Internship

## Project Overview
This project implements an end-to-end supervised machine learning classification pipeline using the Iris dataset.

The objective is to compare Logistic Regression and Decision Tree classifiers using standard classification evaluation metrics.

## Dataset
- Dataset: Iris Dataset
- Total Samples: 150
- Features: 4
- Classes: Setosa, Versicolor, Virginica

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

## Project Workflow
1. Dataset loading
2. Exploratory Data Analysis
3. Missing value and duplicate checking
4. Feature normalization using StandardScaler
5. Train-test split (80:20)
6. Logistic Regression training
7. Decision Tree training
8. Model evaluation
9. Confusion matrix visualization
10. Decision boundary visualization

## Model Performance

| Metric | Logistic Regression | Decision Tree |
|---|---:|---:|
| Accuracy | 93.33% | 96.67% |
| Precision | 93.33% | 96.97% |
| Recall | 93.33% | 96.67% |
| F1-Score | 93.33% | 96.66% |

## Conclusion
Both models performed well on the test dataset. Decision Tree achieved the highest accuracy of 96.67%, outperforming Logistic Regression on this particular test split.

## How to Run

1. Clone the repository.
2. Install dependencies:

   `pip install -r requirements.txt`

3. Launch Jupyter:

   `jupyter notebook`

4. Open `Task_1_Multi_Class_Classification.ipynb`.
5. Run all cells.

## Author
Bansari Patel

## Internship
Datheon – Machine Learning & Data Science Internship