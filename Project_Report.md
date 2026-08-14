# Project Report — Iris Flower Classification

## 1. Project Title

Iris Flower Classification Using Machine Learning

## 2. Objective

The objective of this project is to build a machine learning classification model that can identify Iris flower species based on their physical measurements.

The model classifies flowers into three species:

- Setosa
- Versicolor
- Virginica

## 3. Dataset

The Iris dataset from Scikit-learn is used for this project.

The dataset contains 150 samples and four input features:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

There are three target classes:

- Setosa
- Versicolor
- Virginica

## 4. Tools and Technologies

The following tools and libraries were used:

- Python
- Google Colab
- Jupyter Notebook
- Pandas
- Matplotlib
- Scikit-learn

## 5. Methodology

The project follows these steps:

1. Load the Iris dataset.
2. Explore the dataset.
3. Check the dataset structure and missing values.
4. Visualize the flower measurements.
5. Separate features and target labels.
6. Split the dataset into training and testing sets.
7. Standardize the features.
8. Train a K-Nearest Neighbors (KNN) classifier.
9. Make predictions on the test dataset.
10. Evaluate the model using accuracy, classification report, and confusion matrix.

## 6. Machine Learning Model

The K-Nearest Neighbors (KNN) algorithm was used for classification.

KNN classifies a new data point based on the classes of its nearest neighboring data points.

The features were standardized before training the model to ensure that all measurements contributed appropriately to the distance calculation.

## 7. Model Evaluation

The model was evaluated using a separate test dataset containing 30 samples.

### Accuracy

The model achieved:

**93.33% accuracy**

This means that the model correctly classified 28 out of 30 test samples.

## 8. Classification Report

The classification report produced the following results:

| Class | Precision | Recall | F1-Score |
|---|---:|---:|---:|
| Setosa | 1.00 | 1.00 | 1.00 |
| Versicolor | 0.83 | 1.00 | 0.91 |
| Virginica | 1.00 | 0.80 | 0.89 |

Overall accuracy: **93.33%**

## 9. Results

The model performed very well on the Iris dataset.

- Setosa was classified correctly for all test samples.
- Versicolor achieved a recall of 1.00.
- Virginica achieved a recall of 0.80.
- The overall model accuracy was 93.33%.

The confusion matrix included in the notebook provides a visual representation of the correct and incorrect predictions.

## 10. Conclusion

The Iris Flower Classification project successfully demonstrates a complete machine learning classification workflow.

Using the KNN algorithm, the model achieved an accuracy of **93.33%** on the test dataset.

This project helped demonstrate important machine learning concepts including data exploration, visualization, preprocessing, feature standardization, model training, prediction, and model evaluation.

## 11. Project Files

The GitHub repository contains:

- `CodeAlpha_Iris_Flower_Classification.ipynb` — Complete Jupyter Notebook with code, analysis, visualizations, and model evaluation.
- `README.md` — Project overview and documentation.
- `Project_Report.md` — Detailed project report.

## 12. Internship Task

This project was completed as part of the CodeAlpha Data Science Internship.

**Project:** Iris Flower Classification
