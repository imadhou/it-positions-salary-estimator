# Project Title: Atelier Data Quality and Data Processing

## Project Overview

This project, "Atelier Data Quality and Data Processing," was realized by HOUARI Mourtada and KASMI Ghilas. The goal of this project is to perform data quality assessment and data processing on a dataset related to manager salary survey data from the year 2021. The dataset includes information about managers' salaries, job context, currencies, education, gender, race, country, and more. The project aims to clean the data, perform exploratory data analysis, and build machine learning models to predict salary categories and explore salary distributions.

## Dependencies

The following Python libraries are used in this project and need to be installed before running the code:

- pandas
- matplotlib
- pycountry
- currency_converter
- nltk
- scikit-learn
- tensorflow
- plotly

You can install these libraries using pip:

```
pip install pandas matplotlib pycountry currency_converter nltk scikit-learn tensorflow plotly
```

## Data Exploration

The project begins with data exploration and understanding. The dataset is read into a pandas DataFrame, and various descriptive statistics, histograms, and bar charts are created to explore the data's distribution and properties.

## Data Cleaning

The data cleaning process includes normalizing country names, converting salaries to a consistent currency (USD), and removing irrelevant columns. The dataset is cleaned and processed to prepare it for further analysis and modeling.

## Text Data Preprocessing

Textual data in the dataset, such as job titles and fields, are preprocessed for analysis. Text tokenization, punctuation removal, case folding, lemmatization, and stopword removal are performed to standardize and prepare the textual data for machine learning.

## Data Analysis and Visualization

The project analyzes salary distributions by country, job field, and other categorical variables. Various visualizations, including bar charts and choropleth maps, are created to understand the dataset's characteristics and salary trends.

## Model Building

Two types of models are built for this project:

1. Decision Tree Classifier: A decision tree model is used to classify salary categories based on different features from the dataset.

2. Gradient Boosting Classifier: A gradient boosting model is also trained to predict salary categories more accurately.

3. Linear Regression: A linear regression model is used to predict exact salary values based on various features.

4. Neural Network: A neural network model is implemented to explore the data further and potentially predict salary categories.

## Dimensionality Reduction

Principal Component Analysis (PCA) is applied to reduce the dataset's dimensionality while preserving its variance. It helps visualize the data in lower-dimensional space (3D) to identify patterns and clusters.

## Manifold Learning (t-SNE)

t-SNE (t-Distributed Stochastic Neighbor Embedding) is used for manifold learning to visualize data in a reduced 3D space while preserving the local structure of the data points. The t-SNE visualization helps gain insights into the data distribution and patterns.

## Conclusion

The Atelier Data Quality and Data Processing project aims to clean, preprocess, analyze, and model manager salary survey data. It provides valuable insights into salary distributions and factors affecting salaries based on various features. The project leverages machine learning techniques to classify salary categories and predict salary values. Additionally, visualizations help to understand data distributions, trends, and clusters in a reduced 3D space. The code and findings from this project can be used for further research and analysis related to manager salaries and compensation.
