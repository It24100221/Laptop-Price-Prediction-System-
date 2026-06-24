# Laptop Price Data Preprocessing System

![Python](https://img.shields.io/badge/Python-3.8+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Processing-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML%20Preprocessing-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557C?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Academic%20Project-purple?style=for-the-badge)

## Introduction

This project is a **Laptop Price Data Preprocessing System** developed as an academic group project. The main purpose of this project is to clean and prepare a raw laptop price dataset for future data analysis and machine learning tasks.

The project applies several important data preprocessing techniques such as missing value handling, categorical encoding, one-hot encoding, outlier removal, normalization and scaling, feature selection, and dimensionality reduction.

---

## Problem Statement

Raw datasets often contain missing values, categorical variables, outliers, inconsistent formats, and features with different value ranges. These issues can reduce the quality of analysis and affect the performance of machine learning models.

In laptop price analysis, features such as company, laptop type, RAM, weight, screen size, operating system, CPU, GPU, and price need to be cleaned and transformed before they can be used effectively.

---

## Objectives

- Clean and prepare the raw laptop price dataset.
- Handle missing values and inconsistent data.
- Convert categorical data into numerical format.
- Detect and remove outliers from important numerical columns.
- Normalize and scale numerical features.
- Select the most useful features for analysis.
- Reduce dimensionality while preserving important information.
- Generate a final preprocessed dataset for future machine learning models.

---

## Dataset

| Item | Description |
|---|---|
| Dataset Name | Laptop Price Dataset |
| Dataset Type | Tabular / Structured Dataset |
| Source File | `data/Raw/laptop_price.csv` |
| Final Output | `results/outputs/preprocessed_laptopPrice.csv` |
| Domain | Data Science / Data Preprocessing / Price Analysis |

---

## Key Preprocessing Steps

### 1. Missing Value Handling

Identified missing values in the dataset and handled them to improve data completeness and avoid errors during analysis.

### 2. Categorical Encoding

Converted categorical columns into numerical format so they can be used in data analysis and machine learning workflows.

### 3. One-Hot Encoding

Applied one-hot encoding to selected categorical features to represent categories without creating false ranking relationships.

### 4. Outlier Removal

Detected and handled extreme values to reduce the effect of outliers on the final dataset.

### 5. Normalization and Scaling

Scaled numerical features to bring values into a similar range and improve consistency.

### 6. Feature Selection

Selected important features and removed less useful columns to improve dataset quality.

### 7. Dimensionality Reduction

Reduced the number of features while preserving meaningful information from the dataset.

---

## Tech Stack

| Category | Technology |
|---|---|
| Programming Language | Python |
| Development Environment | Jupyter Notebook / Google Colab |
| Data Handling | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Machine Learning Tools | Scikit-learn |
| Output Format | CSV, PNG visualizations |

---

## Repository Structure

```text
2025_Y2_S1_KUR_08/
│
├── data/
│   └── Raw/
│       └── laptop_price.csv
│
├── notebooks/
│   ├── IT24103132_missing_values_handling.ipynb
│   ├── IT24103206_Encoding_categorical_variables.ipynb
│   ├── IT24103639_One_Hot_Encoding.ipynb
│   ├── IT24100221_Outlier_Removal.ipynb
│   ├── IT24103155_Normalization and scaling.ipynb
│   ├── IT24100221_Feature_Selection.ipynb
│   └── IT24103186_Dimension_Reduction.ipynb
│
├── results/
│   ├── eda_visualizations/
│   │   ├── Before_Removal_Outliers.png
│   │   ├── After_Removal_Outliers.png
│   │   ├── Missing_Values_Handling.png
│   │   ├── Filter Method.png
│   │   ├── Embedded Method.png
│   │   ├── Dimension_Reduction.png
│   │   └── other visualization outputs
│   │
│   └── outputs/
│       └── preprocessed_laptopPrice.csv
│
├── group_pipeline.ipynb
└── README.md
```

---

## Outputs

| Output | Location |
|---|---|
| Final cleaned dataset | `results/outputs/preprocessed_laptopPrice.csv` |
| EDA and preprocessing visualizations | `results/eda_visualizations/` |
| End-to-end preprocessing pipeline | `group_pipeline.ipynb` |
| Individual preprocessing notebooks | `notebooks/` |

---

## How to Run

### Prerequisites

Install Python and the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### Run Locally

1. Clone the repository:

```bash
git clone https://github.com/<your-username>/<your-repository-name>.git
cd <your-repository-name>
```

2. Open Jupyter Notebook:

```bash
jupyter notebook
```

3. Run the main notebook:

```text
group_pipeline.ipynb
```

4. The preprocessed dataset will be generated at:

```text
results/outputs/preprocessed_laptopPrice.csv
```

---

## Google Colab Usage

1. Upload the project folder to Google Drive.
2. Open `group_pipeline.ipynb` in Google Colab.
3. Make sure the dataset path points to:

```text
data/Raw/laptop_price.csv
```

4. Run all cells.
5. Download the generated CSV and visualizations from the `results/` folder.

---

## Team Members and Roles

| Team Member | IT Number | Key Contribution |
|---|---|---|
| E.M.N.A. Ekanayake | IT24100221 | Feature Selection / Outlier Removal |
| A.M.N. Aluthgoda | IT24103132 | Missing Values Handling |
| T.L.D. Sathsarani | IT24103155 | Normalization and Scaling |
| B.G.S.L. Liyanassooriya | IT24103186 | Dimensionality Reduction |
| K.V.U. Jayananda | IT24103206 | Encoding Categorical Variables |
| A.P.D.O.C. Wijesinghe | IT24103639 | One-Hot Encoding |

---

## Project Goals

- Understand the importance of preprocessing in data science.
- Apply real preprocessing techniques to a structured dataset.
- Create a clean dataset suitable for future laptop price prediction.
- Improve practical skills in Python, Pandas, Scikit-learn, visualization, and teamwork.

---

## Contributing

This project was developed as an academic group project. Contributions, suggestions, and improvements are welcome for learning purposes.

---

## License

This project is for educational purposes only.
