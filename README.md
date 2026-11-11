# Airline Passenger Satisfaction Prediction

A machine learning project that aims to predict airline passenger satisfaction "using logistic regression" based on passenger demographics, travel details, and in-flight service ratings.

## 1. Team Members

| Name | GitHub Username | Role |
|---|---|---|
| Syed Ibrahim Affan | ibrahim-affan | Documentation Lead |
| Naitik | naitik83 | Video Lead |
| Gunjan | gunjan-iitrpr | PPT Lead |
| Anubhab Chakraborty | anubhab-chakraborty-26-1324 | Execution Lead |

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
The `train.csv` file contains 310 missing values, located in `Arrival Delay in Minutes`. It has no duplicate rows.

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

The project uses Python and the following libraries and tools:

| Technology | Version | Purpose |
|---|---:|---|
| Python | 3.13.14 | Main programming language |
| Pandas | 3.0.6 | Data handling and manipulation |
| NumPy | 2.5.2 | Numerical computations |
| Scikit-learn | 1.9.1 | Machine learning models and evaluation |
| Matplotlib | 3.11.2 | Data visualization |
| Seaborn | 0.13.2 | Statistical data visualization |
| ipynb | 0.5.1 | Model serialization |
| IPython | 9.16.1 | Interactive Python environment |
| ipykernel | 7.3.0 | Jupyter notebook kernel |
| Jupyter Client | 8.9.1 | Jupyter notebook communication |
| Jupyter Core | 5.9.1 | Jupyter functionality |
| Traitlets | 5.16.1 | Configuration support |



## 7. Project Structure

```text
airline-passenger-satisfaction/
│
├── presentation/
│   └── FinalPPT.pptx
│
├── src/
│   ├── datasets/
│   │   ├── test.csv
│   │   └── train.csv
│   │
│   ├── data_preprocessing.ipynb
│   ├── data_visualization.ipynb
│   ├── main.ipynb
│   ├── model_train_test.ipynb
│   └── performance_analysis.ipynb
│
├── .gitattributes
├── README.md
└── requirements.txt
```




## 8. Installation and Execution

### Prerequisites
- Python 3.13.14
- Jupyter Notebook
- Git (for cloning the repository)
- pip (Python package manager)
- Microsoft VS Code
Other requisites and their versions are mentioned in the requirements.txt

### Step 1: Go to your preferred folder

Open CMD.
Go to the folder where you want to clone the repository.
```bash
cd path\to\your\folder
```
### Step 2: Clone the repository

```bash
git clone https://github.com/ibrahim-affan/airline-passenger-satisfaction.git
```

### Step 3: Enter the cloned repository

```bash
cd airline-passenger-satisfaction
```

### Step 4: Create a python virtual environment

```bash
python -m venv .venv
```

### Step 5: Activating the virtual environment

```bash
.venv\Scripts\activate
```

### Step 6: Installing requirements

```bash
pip install -r requirements.txt
```

### Step 7: Enter the src folder

```bash
cd src
```

### Step 8: Open the main.ipynb file in VS Code

```bash
code main.ipynb
```

1. Select .venv (3.13.14) as the environment.
2. Execute each and every cell of the main.ipynb file.
3. First you will get a detailed Exploratory Data Analysis with a lot of graphs.
5. Next in the data processing portion, the empty entries in the Arrival Delays have been updated with the median value in both df_train and df_test.
6. Encoding of data frames has also been done.
7. The Logistic Regression model is then trained on the training dataset and its predictions on the testing dataset are stored for analysis.
8. The performance analysis portion shows you various images, graphs and performance metrics to analyze model performance. 


## 9. Model Evaluation and Results

### Model Used
**Logistic Regression** was used as the machine learning classification algorithm to predict airline passenger satisfaction.

### Performance Metrics

| Evaluation Metric | Score |
|---|---:|
| Accuracy | 87.16% |
| Precision | 0.87 |
| Recall | 0.83 |
| F1-Score | 0.85 |

### Results Summary

- **Accuracy (87.16%):** The model correctly classified 87.16% of the evaluated samples.
- **Precision (0.87):** Measures the proportion of positive predictions that were correct.
- **Recall (0.83):** Measures the proportion of actual positive cases correctly identified.
- **F1-Score (0.85):** Represents the harmonic mean of precision and recall.

### Conclusion

The Logistic Regression model achieved an accuracy of 87.16%, demonstrating good performance in predicting airline passenger satisfaction. Also it has a good F1 Score, suggesting that it balances both precision and recall and it has excellent predictive performance.


## 10. Presentation and Demonstration

- **Project Presentation:** https://github.com/ibrahim-affan/airline-passenger-satisfaction/blob/main/presentation/FinalPPT.pptx
- **Project Demonstration Video:** https://drive.google.com/file/d/1rUtORzWiD9h2oddZm1lQS4Fh3n5Sk6gy/view?usp=share_link

## 11. AI Usage Disclosure

ChatGPT has been used to assist with project planning, understanding documentation requirements, and preparing the initial README structure. Gemini has been used for making some graphs in the data visualization and prediction analysis. 
## 12. Acknowledgement

We acknowledge the Kaggle contributor for providing the Airline Passenger Satisfaction dataset used in this project. We also thank our A.I. faculties at I.I.T. Ropar for providing us guidance in the form of assignments and hands-on sessions.

