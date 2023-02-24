# Udacity_DataSc_P4
Udacity Data Science Project 4 - Customer Segmentation Report for Arvato

## Objectives of Project


## Recommended initial Setup & Installations

They are quite some libraries used across the project, all referenced in the requirements.txt file. For a step by step setup ou can follow those 4 steps:

- Create a virtual environment python -m venv .venv

- Set Execution Policy Settings (optional only if next step leads to error) Set-ExecutionPolicy Unrestricted -Scope Process or Set-ExecutionPolicy RemoteSigned

- Activate venv ..venv\Scripts\activate

- Install required librairies pip install -r requirements.txt pip freeze > requirements.txt (to update requirements file with all installed packages)

## How to run the project

The whole conent of the project is held in a single notebook: Recommendations_with_IBM.ipynb.

Also for a simple read through an html version of the notebook is available : Recommendations_with_IBM.html

## Files Descriptions

- `Udacity_AZDIAS_052018.csv`: Demographics data for the general population of Germany; 891 211 persons (rows) x 366 features (columns).
- `Udacity_CUSTOMERS_052018.csv`: Demographics data for customers of a mail-order company; 191 652 persons (rows) x 369 features (columns).
- `Udacity_MAILOUT_052018_TRAIN.csv`: Demographics data for individuals who were targets of a marketing campaign; 42 982 persons (rows) x 367 (columns).
- `Udacity_MAILOUT_052018_TEST.csv`: Demographics data for individuals who were targets of a marketing campaign; 42 833 persons (rows) x 366 (columns).

## High Level Project Steps


## Licensing, Authors, Acknowledgements, etc.

I thank the data provider Arvato for the availibility of its dataset and share of project ideas.

Here are some help / resources used during this project (non-exhaustive):

- https://datatofish.com/copy-file-python/
- https://jakevdp.github.io/PythonDataScienceHandbook/05.09-principal-component-analysis.html
- https://stackabuse.com/implementing-pca-in-python-with-scikit-learn/