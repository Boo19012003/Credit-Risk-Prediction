# Credit Risk Prediction Project

This project focuses on building a machine learning model to predict the likelihood of customer default (credit risk). This is a crucial problem in the Banking and Finance sector aimed at minimizing risk and optimizing the lending process.

## Project Objectives
- **Exploratory Data Analysis (EDA):** Identify key factors influencing credit risk.
- **Model Development:** Build and evaluate Classification models to predict the probability of customer default.
- **Optimization:** Fine-tune models to achieve the best possible performance.

## Folder Structure
```plaintext
├── Dataset/
│   ├── Credit Risk Dataset.xlsx - Credit Risk Data.csv  # Original project data
│   └── Credit Risk Dataset.xlsx - Data Dictionary.csv # Data dictionary/column explanations
├── Notebook/
│   ├── EDA.ipynb        # Data analysis, visualization, and preprocessing
│   └── Model_2.2.ipynb  # Model building, training, and evaluation
└── README.md
```

## Dataset
The dataset contains detailed information about customers, including:
- Personal income.
- Age.
- Loan amount.
- Credit history.
- Loan purpose.
- Loan status (The prediction target).

For more details on each column, please refer to the `Data Dictionary.csv` file in the `Dataset/` directory.

## Technologies Used
- **Language:** Python
- **Key Libraries:**
  - **Data Manipulation:** Pandas, NumPy
  - **Visualization:** Matplotlib, Seaborn
  - **Machine Learning:** Scikit-learn (plus XGBoost/LightGBM if used)

## Workflow
1. **Data Preprocessing:** Handling missing values, treating outliers, and encoding categorical variables.
2. **Exploratory Data Analysis (EDA):** Analyzing data distributions and correlations between features.
3. **Model Building:** Testing and comparing various machine learning algorithms.
4. **Evaluation:** Assessing performance using metrics such as Accuracy, Precision, Recall, F1-score, and AUC-ROC.
