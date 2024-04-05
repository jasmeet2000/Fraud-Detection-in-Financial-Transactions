# Fraud Detection in Financial Transactions

## Project Overview

This repository contains the code and documentation for the "Fraud Detection in Financial Transactions" project undertaken as part of the AMOD-5610: Big Data Major Research Paper course. 

The project aims to address the challenges of fraud detection in financial transactions using big data analytics and machine learning techniques, with a specific focus on mobile money transactions.


## Authors

- Ayush Sharma (0774583)

- Jasmeet Singh Saini (0758054)


## Getting Started

To run Jupyter Notebook (.ipynb) files, you need the following:

1. Python Installation:

To run the code, make sure you have **Python** installed on your machine (*Python 3.7.0*). Then, you can install the required libraries, which are discussed below in the next section. 


2. Jupyter Notebook Installation:

Jupyter Notebook is often included when you install Python using Anaconda. If you don't have Anaconda, you can install Jupyter Notebook using pip:

``` bash
pip install notebook
```


3. Libraries and Dependencies:

Ensure that you have all the required libraries and dependencies installed. You can use the following command to install them if you haven't already (in terminal) :-

``` bash
pip install matplotlib numpy pandas seaborn xgboost lightgbm imbalanced-learn scikit-learn
```

or write one by one:-
``` bash
pip install pandas 
pip install numpy 
pip install matplotlib 
pip install seaborn 
pip install scikit-learn
pip install xgboost
pip install lightgbm 
pip install imbalanced-learn

```

Libraries Used:-

- **Matplotlib**: A 2D plotting library for creating static, animated, and interactive visualizations.

- **NumPy**: A library for numerical operations in Python.

- **Pandas**: A data manipulation library for handling and analyzing structured data.

- **Seaborn**: A statistical data visualization library based on Matplotlib.

- **scikit-learn**: A library for simple and efficient tools for predictive data analysis. For machine learning algorithms and evaluation metrics.

- **XGBoost**: For gradient boosting.

- **LightGBM**: For gradient boosting.

- **Imbalanced-Learn (imblearn)**: For dealing with imbalanced datasets, including oversampling and undersampling techniques.

Note: This code contains code snippets for performing Exploratory Data Analysis (EDA) using Python. The code utilizes various data visualization libraries, including Matplotlib, NumPy, Pandas, Seaborn, and SciPy.


5. Download the Code Files:

Download the .ipynb files for Blackboard.


6. Start Jupyter Notebook:

Type the following command to start Jupyter Notebook:-

``` bash 
jupyter notebook
```

Or open the anaconda software and then click on 'Open Lab'. This will open the Jupyter Notebook in the http://localhost:8888/


7. Upload the Pyton code (.ipny File) and the Dataset (.csv file):

Load the Pyton code (.ipny File) and the Dataset (.csv file) by clicking on the upload file in the top left of the Jupyter Notebook.

8. Loading the Dataset:

The dataset file name is 'train.csv'. Make Sure you put that in the same directory otherwise you need to give the path of the CSV File. (or Open a terminal or command prompt and navigate to the directory where your .ipynb files are located using the cd command)

```python
# Load the dataset
file_path = 'financial_transactions_dataset.csv'
df         = load_dataset(file_path)
```

9. Open and Run the .ipynb File:

In the Jupyter Notebook interface, navigate to the directory where your .ipynb file is located. Click on the .ipynb file to open it. Run the code cells one by one or use the "Run All" option from the toolbar to execute all cells.


