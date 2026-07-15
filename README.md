# Bank_management_model
## Project Overview

This project focuses on preprocessing the **Bank Marketing Dataset (bank-full.csv)** using **Google Colab**. The dataset contains information collected from direct marketing campaigns of a Portuguese banking institution. 
----------

## Dataset Information

- **Dataset Name:** bank-full.csv
- **Source:** UCI Machine Learning Repository
- **Number of Records:** 45,211
- **Number of Features:** 17
- **Target Variable:** `y`
  - yes (Customer subscribed to a term deposit)
  - no (Customer did not subscribe)
- **Dataset Link:** https://archive.ics.uci.edu/ml/datasets/bank+marketing

------------------ 
  
## Steps Performed

### 1. Import Required Libraries
  The necessary Python libraries were imported for data analysis and preprocessing.
### 2. Load Dataset
  The dataset was loaded using Pandas.
### 3. Exploratory Data Analysis
  Performed:
- Shape of the dataset
- Data types
- Summary statistics
- Column names
- Information about missing values
### 4. Preprocesing
  - Checked for missing values.
  - No missing values were found in the dataset.
  - Categorical variables were encoded using:
    - Label Encoding
    - One-Hot Encoding
  - Numerical features were scaled using:
    - Minmax Scaler 

---------

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---------

## Instructions to Run the Project

### Step 1
Clone the repository.
```bash
git clone <repository-link>
```
### Step 2
Open Google Colab.
### Step 3
Upload:
- bank-full.csv
- Bank_Preprocessing.ipynb
or mount Google Drive.
### Step 4
Install the required libraries if necessary.
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```
### Step 5
Run all the cells in the notebook sequentially.

-----------------


## Inference
- There are no missing values.
- The dataset is imbalanced, with significantly more **"no"** responses than **"yes"** responses.
- There are 7 numerical columns and 10 categorical columns.

---------------------

## Contributions
- 1. Skeleton - Priya Shill
  2. Data Reading and EDA - Arya A R
  3. Data Cleaning - Priya Shill
  4. Data Transformations - Ananthakrishnan M
  5. Readme - Arya A R
