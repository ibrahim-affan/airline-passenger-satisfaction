# Airline Passenger Satisfaction Prediction

A machine learning project that aims to predict airline passenger satisfaction based on passenger demographics, travel details, and in-flight service ratings.

## 1. Team Members

| Name | GitHub Username | Role |
|---|---|---|
| Syed Ibrahim Affan | ibrahim-affan | Documentation Lead |
| Naitik | naitik83 | Video Lead |
| Gunjan | gunjan-iitrpr | PPT Lead |
| Anubhab Chakraborthy | anubhab-chakraborthy-26-1324 | Execution Lead |

All team members are expected to contribute to the project development and maintain their individual GitHub contributions.

## 2. Problem Statement

Airline passenger satisfaction depends on several factors, including service quality, comfort, travel class, customer experience, and flight delays.

The objective of this project is to develop a machine learning classification model that predicts whether an airline passenger is satisfied or neutral/dissatisfied using the available passenger data.

## 3. Dataset Information

**Dataset Name:** Airline Passenger Satisfaction

**Dataset Source:** [Kaggle - Airline Passenger Satisfaction](https://www.kaggle.com/datasets/teejmahal20/airline-passenger-satisfaction)

**Dataset Contributor:** teejmahal20

The project uses the original Kaggle dataset, consisting of two CSV files:

| File | Number of Records | Number of Columns | Purpose |
|---|---:|---:|---|
| `train.csv` | 103,904 | 25 | Model training and validation |
| `test.csv` | 25,976 | 25 | final model evaluation |

**Target Variable:** `satisfaction`

The target variable contains two classes:
- `satisfied`
- `neutral or dissatisfied`

The dataset includes:
- Passenger demographics
- Customer type and travel class
- Flight distance and delays
- In-flight service ratings
- Passenger satisfaction labels

The `test.csv` file contains 83 missing values, located in `Arrival Delay in Minutes`. It has no duplicate rows.

The training and testing datasets will be kept separate for model development and evaluation.

## 4. Project Objectives

- Understand the factors affecting airline passenger satisfaction.
- Perform exploratory data analysis.
- Handle missing values and preprocess the dataset.
- Select relevant features for prediction.
- Apply suitable machine learning classification algorithms.
- Evaluate model performance.
- Predict passenger satisfaction.

## 5. Project Workflow

The planned project workflow is:

1. Dataset collection
2. Exploratory Data Analysis (EDA)
3. Data cleaning and preprocessing
4. Feature selection and encoding
5. Model training
6. Model evaluation
7. Results visualization
8. Passenger satisfaction prediction

## 6. Technologies Used

The technologies and libraries will be documented according to the final implementation.

Expected tools may include:

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 7. Current Project Structure

```text
airline-passenger-satisfaction/
│
├── .gitattributes
├── README.md
├── train.csv
└── test.csv
```

Additional files for Python source code, notebooks, dependencies, results, presentation, and demonstration video will be added as the project develops.

## 8. Installation and Execution

The exact Python version, dependencies, installation commands, and execution instructions will be added after the Execution Lead finalizes the implementation.

A `requirements.txt` file will list the required Python libraries and their versions.

## 9. Model Evaluation and Results

The model will be evaluated using suitable classification metrics, such as:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

Actual evaluation results, graphs, and screenshots will be added after model implementation.

## 10. Presentation and Demonstration

- **Project Presentation:** To be added.
- **Project Demonstration Video:** To be added.

## 11. AI Usage Disclosure

ChatGPT has been used to assist with project planning, understanding documentation requirements, and preparing the initial README structure.

Any AI-assisted code, explanations, or other content used in the final project will be reviewed and verified by the team. Additional AI tools and their uses will be disclosed if applicable.

## 12. Acknowledgement

We acknowledge the Kaggle contributor for providing the Airline Passenger Satisfaction dataset used in this project.

