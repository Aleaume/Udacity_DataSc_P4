# Udacity_DataSc_P4
Udacity Data Science Project 4 - Customer Segmentation Report for Arvato

## Objectives of Project
This project is a complete Data Science Analysis of how the use of Data Wrangling, Clustering and Machine Learning can help companies identify potential future customers.
The context is simple, a mail-order company wants to target efficiently potential future customers.

The project main findings are also listed in an article here : https://medium.com/@aliaume64/a-guide-to-optimal-customer-targeting-using-data-science-f8956a5d319d
## Recommended initial Setup & Installations

They are quite some libraries used across the project, all referenced in the requirements.txt file. For a step by step setup ou can follow those 4 steps:

- Create a virtual environment python -m venv .venv

- Set Execution Policy Settings (optional only if next step leads to error) Set-ExecutionPolicy Unrestricted -Scope Process or Set-ExecutionPolicy RemoteSigned

- Activate venv ..venv\Scripts\activate

- Install required librairies pip install -r requirements.txt pip freeze > requirements.txt (to update requirements file with all installed packages)

## How to run the project

The whole conent of the project is held in a single notebook: Arvato Project Workbook.ipynb.


## Files Descriptions

- `Udacity_AZDIAS_052018.csv`: Demographics data for the general population of Germany; 891 211 persons (rows) x 366 features (columns).
- `Udacity_CUSTOMERS_052018.csv`: Demographics data for customers of a mail-order company; 191 652 persons (rows) x 369 features (columns).
- `Udacity_MAILOUT_052018_TRAIN.csv`: Demographics data for individuals who were targets of a marketing campaign; 42 982 persons (rows) x 367 (columns).
- `Udacity_MAILOUT_052018_TEST.csv`: Demographics data for individuals who were targets of a marketing campaign; 42 833 persons (rows) x 366 (columns).

## High Level Project Steps
0. Get to Know the Data
In this step, we get a first view of the dataset. Data Analysis, identification of types, missing values.
Then we also tackle preprocessing steps (cleaning, imputing, normalization).

1. Customer Segmentation Report
You'll begin the project by using unsupervised learning methods to analyze attributes of established customers and the general population in order to create customer segments.

2. Supervised Learning Model
You'll have access to a third dataset with attributes from targets of a mail-order campaign. You'll use the previous analysis to build a machine learning model that predicts whether or not each individual will respond to the campaign.

## Results & Going further

With the current model we reach an Area under the ROC Curve score of about ~68% with our fine tuned Logistic Regression.
There is definitely room for improvement in the number of different classifiers models to try (GradientBoostingClassifier, CatBoostClassifier …).

Also, some more attention could be brought to the data cleaning step in hope of getting a better result.

PCA analysis could also in a next step be turned into profit for the Model training phase.

## Licensing, Authors, Acknowledgements, etc.

I thank the data provider Arvato for the availibility of its dataset and share of project ideas.

Here are some help / resources used during this project (non-exhaustive):
### General Data Science

- https://datatofish.com/copy-file-python/
- https://pandas.pydata.org/docs/dev/getting_started/intro_tutorials/03_subset_data.html
- https://stackoverflow.com/questions/48750762/how-to-use-dataframe-rename-to-rename-a-dataframe-index-not-inplace
- https://pandas.pydata.org/docs/reference/api/pandas.MultiIndex.to_flat_index.html
- https://pandas.pydata.org/docs/user_guide/merging.html
- https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.transpose.html
- https://matplotlib.org/stable/tutorials/introductory/pyplot.html#sphx-glr-tutorials-introductory-pyplot-py

### PCA:

- https://jakevdp.github.io/PythonDataScienceHandbook/05.09-principal-component-analysis.html
- https://stackabuse.com/implementing-pca-in-python-with-scikit-learn/
- https://towardsdatascience.com/pca-clearly-explained-how-when-why-to-use-it-and-feature-importance-a-guide-in-python-7c274582c37e

### Clustering:
- https://realpython.com/k-means-clustering-python/
- https://scikit-learn.org/stable/auto_examples/cluster/plot_kmeans_silhouette_analysis.html#sphx-glr-auto-examples-cluster-plot-kmeans-silhouette-analysis-py
- https://scikit-learn.org/stable/modules/generated/sklearn.metrics.silhouette_score.html


### Modeling:
- https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.GridSearchCV.html
- https://www.projectpro.io/recipes/optimize-hyper-parameters-of-logistic-regression-model-using-grid-search-in-python
- https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html
- https://refactored.ai/microcourse/notebook?path=content%2F06-Classification_models_in_Machine_Learning%2F01-Classification_-_Logistic_Regression%2F02-Advanced_Logistic_Regression.ipynb#:~:text=The%20dual%20formulation%20is%20only,to%20specify%20the%20optimization%20algorithm.
- https://www.projectpro.io/recipes/optimize-hyper-parameters-of-logistic-regression-model-using-grid-search-in-python
- https://towardsdatascience.com/hyperparameter-tuning-the-random-forest-in-python-using-scikit-learn-28d2aa77dd74
- https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html

