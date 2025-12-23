# Student Depression Analysis & Prediction

## Overview
This project analyzes student depression data and applies machine learning
techniques to understand and predict depression-related outcomes.

The notebook demonstrates a complete ML workflow, including:
- Data preprocessing
- Feature engineering
- Exploratory data visualization
- Training and evaluating classification models

This project was developed as part of an ML bootcamp.

---

## Dataset
The dataset used in this project contains information related to students,
including demographic, academic, lifestyle, and mental health factors.

The dataset is provided as a CSV file and is **not included** in this repository
due to size/licensing considerations.

You can download it from:
👉  https://drive.google.com/file/d/1oTg6WCGHHXvx1-ux_Q4YY1ch0eVnQnpZ/view?usp=sharing

After downloading, place the CSV file in a `data/` folder or update the dataset
path in `notebook.ipynb` accordingly.


## Preprocessing
The following preprocessing steps were performed:
- Column cleaning and formatting
- Handling categorical variables
- Encoding binary and multi-class features
- One-hot encoding for features such as:
  - Dietary habits
  - City
  - Profession
  - Degree

---

## Feature Engineering & Visualization
- Feature transformations were applied to prepare the data for modeling
- Visualizations were used to explore patterns and relationships in the data

---

## Machine Learning Models
The following classification models were trained and evaluated:
- Logistic Regression
- Decision Tree
- Random Forest

Model performance was evaluated using standard classification metrics.

---

## How to Run
You can run this project using:
- **Google Colab** (recommended)
- Jupyter Notebook (local environment)

Steps:
1. Download the dataset
2. Open `notebook.ipynb`
3. Run all cells from top to bottom

---

## Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn

---

## Notes
- This notebook was originally developed in Google Colab
- Outputs and visualizations are included for clarity

