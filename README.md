# Exploratory Data Analysis (EDA) for Netflix Movies Dataset
This repository contains the code and data for conducting Exploratory Data Analysis (EDA) on a dataset of Netflix movies. The EDA process involves analyzing various aspects of the dataset to understand its structure, relationships between variables, and uncover any patterns or trends present in the data.

## Dataset
The dataset used for this analysis contains information about Netflix movies, including attributes such as title, genre, premiere date, runtime, IMDB score, and language. The dataset is stored in a CSV file named netflix_movies.csv taken from Kaggle.

## Steps Taken
The EDA process involved the following steps:

Data Loading: The dataset was loaded into a pandas DataFrame using Python.
Data Cleaning: The dataset was checked for missing values, duplicates, and inconsistencies. 
Univariate Analysis: Basic statistics and visualizations were generated for individual variables to understand their distributions and summary statistics. Pie Chart, box plots, Line plots, Histograms and KDE plots were used to visualize numerical variables.
Segmented Univariate Analysis: The dataset was segmented based on certain criteria (e.g., genre), and univariate analysis was performed for each segment separately.
Bivariate Analysis: Relationships between pairs of variables were explored using scatter plots, line plots, and heatmaps. Correlation analysis was conducted to quantify the strength and direction of relationships between numerical variables.

## Code and Visualization
The code for performing the EDA, including data loading, cleaning, and analysis, is provided in a Jupyter Notebook named EDA.ipynb.

## Conclusion
The EDA process provided valuable insights into the Netflix movies dataset, including the distribution of movie attributes, relationships between variables, and trends over time. The findings from this analysis can inform further exploration or modeling tasks and contribute to a better understanding of the dataset.
