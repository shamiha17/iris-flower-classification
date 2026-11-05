# Iris Flower Classification – Machine Learning

## Project Overview

This project focuses on building and evaluating machine learning models to classify Iris flowers into three species: **Setosa, Versicolor, and Virginica**.

The project uses the Iris dataset and compares two classification algorithms: Logistic Regression and Decision Tree Classifier.

## Objectives

- Explore and understand the Iris dataset.
- Perform Exploratory Data Analysis (EDA).
- Visualize feature relationships and correlations.
- Split the dataset into training and testing sets.
- Train Logistic Regression and Decision Tree models.
- Evaluate and compare model performance using classification metrics.

## Dataset

The project uses the Iris dataset, which contains 150 samples and four numerical features.

**Features:**
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

**Target Variable:** Species

The dataset contains three classes:
- Iris Setosa
- Iris Versicolor
- Iris Virginica

**Dataset Source:** [Iris Dataset – Seaborn GitHub](https://github.com/mwaskom/seaborn-data/blob/master/iris.csv)

## Technologies and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook / Google Colab

## Project Workflow

1. **Data Loading:** Load the Iris dataset using Pandas.
2. **Data Exploration:** Inspect dataset structure, statistical summaries, missing values, and class distribution.
3. **Exploratory Data Analysis:** Visualize feature relationships using pair plots and correlation heatmaps.
4. **Data Preprocessing:** Separate features and target variables and split the dataset into 80% training and 20% testing data.
5. **Feature Scaling:** Apply StandardScaler for Logistic Regression.
6. **Model Training:** Train Logistic Regression and Decision Tree Classifier.
7. **Model Evaluation:** Evaluate both models using accuracy, precision, recall, and F1-score.
8. **Visualization:** Display confusion matrices and compare model performance.

## Machine Learning Models

### 1. Logistic Regression
A classification algorithm used to predict the probability of a sample belonging to a particular class. StandardScaler is applied before training.

### 2. Decision Tree Classifier
A tree-based classification algorithm that makes predictions using a sequence of feature-based decisions. Feature scaling is not required for this model.

## Evaluation Metrics

The models are evaluated using:

- Accuracy
- Precision (Macro Average)
- Recall (Macro Average)
- F1-Score (Macro Average)
- Confusion Matrix
- Classification Report

## Results

The performance of both models is compared using the evaluation metrics above.

**Note:** Actual metric values will be added after executing the notebook.

## How to Run the Project

1. Clone this repository:

   ```bash
   git clone https://github.com/YOUR-USERNAME/iris-flower-classification.git
   ```

2. Navigate to the project folder:

   ```bash
   cd iris-flower-classification
   ```

3. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```

4. Open the Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

5. Open `Task1_Iris_Classification.ipynb` and run all cells.

   Alternatively, upload the notebook to Google Colab and execute it there.

## Repository Structure

```text
iris-flower-classification/
│
├── Task1_Iris_Classification.ipynb
├── README.md
└── requirements.txt
```

## Conclusion

This project demonstrates a complete beginner-friendly machine learning classification workflow, including data exploration, preprocessing, model training, evaluation, and visualization.

By comparing Logistic Regression and Decision Tree Classifier, the project provides practical experience in understanding and evaluating classification algorithms.

## Author

**Shamiha Jahan**

GitHub: (https://github.com/shamiha17)

---

*This project was completed as part of the Datheon Machine Learning & Data Science Internship Task 1.*
