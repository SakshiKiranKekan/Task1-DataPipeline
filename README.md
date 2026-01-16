# Task-1: Data Pipeline Development (ETL)

## Internship: CODTECH  
## Domain: Data Science  

---

## Project Overview
This project demonstrates the development of an **automated Data Pipeline** for **data preprocessing, transformation, and loading (ETL)** using **Python**, **Pandas**, and **Scikit-learn**.

The pipeline automates the complete workflow of:
- Extracting raw data from a CSV file
- Cleaning and preprocessing the dataset
- Transforming numerical and categorical features
- Exporting the processed data into a new CSV file for further analysis

This task is completed as part of the **CODTECH Data Science Internship – Task 1**.

---

## Objective
To build a modular and reusable **ETL pipeline** that:
1. Extracts structured data from a CSV dataset  
2. Applies preprocessing and feature transformations  
3. Loads the transformed data for analysis or machine learning tasks  

---

## Dataset
- **Source:** Kaggle – Titanic Dataset  
- **File Used:** `train.csv`  
- **Description:** The dataset contains passenger information such as age, gender, passenger class, fare, and the target variable `Survived`.

---

## Tools & Technologies Used
- Python  
- Pandas  
- Scikit-learn  
- Google Colab / Jupyter Notebook  

---

## ETL Pipeline Workflow

### Extract
- Loaded the dataset using `pandas.read_csv()`

### Transform
- Handled missing values using forward fill method
- Separated features and target variable
- Identified numerical and categorical columns
- Applied:
  - **StandardScaler** for numerical feature scaling
  - **OneHotEncoder** for categorical feature encoding
- Combined transformations using **ColumnTransformer**
- Automated preprocessing using **Scikit-learn Pipeline**

### Load
- Converted the transformed output into a DataFrame
- Saved the cleaned and transformed data as `processed_data.csv`

---

## Project Structure
Task-1-Data-Pipeline/
│
├── train.csv
├── processed_data.csv
├── Task1_Data_Pipeline.ipynb
└── README.md

---

## How to Run the Project
1. Open the notebook `Task1_Data_Pipeline.ipynb` in Google Colab or Jupyter Notebook  
2. Upload `train.csv` to the working directory  
3. Run all cells sequentially  
4. The processed dataset will be saved as `processed_data.csv`

---

## Output
- A fully automated ETL data preprocessing pipeline
- Cleaned and transformed dataset ready for machine learning workflows

---

## Conclusion
This project demonstrates a structured and efficient approach to building a **data preprocessing and ETL pipeline** using industry-standard libraries.  
It follows best practices in data handling and automation and fulfills the requirements of **CODTECH Task-1**.

---

## Author
**Sakshi Kekan**  
Data Science Intern – CODTECH
