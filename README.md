# Titanic Dataset Exploration

This project explores the Titanic dataset, focusing on data visualization and initial data analysis. The dataset is sourced from [Data Science Dojo's Titanic dataset](https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv).

## Overview

This project uses Python libraries such as `pandas`, `numpy`, `seaborn`, and `matplotlib` to load, analyze, and visualize various aspects of the Titanic dataset, specifically focusing on passenger survival rates and characteristics. 

## Requirements

To run the code in this project, you'll need:

- Python 3.x
- `pandas`
- `numpy`
- `seaborn`
- `matplotlib`

Install the required packages with:

```bash
pip install pandas numpy seaborn matplotlib
Project Structure
Data Loading: Loads the Titanic dataset directly from the GitHub link.
Data Exploration: Examines the dataset's structure, including data types, missing values, and summary statistics.
Data Visualization: Generates visualizations to better understand relationships between features and survival.
Visualizations
Count of Survivors: A count plot showing the number of passengers who survived (Survived = 1) and those who did not (Survived = 0).
Age Distribution: A histogram with a kernel density estimate (KDE) overlay, visualizing the age distribution of passengers.
Age by Survival: A box plot comparing the age distribution for passengers who survived and those who did not.
Survival Rate by Gender: A bar plot showing the survival rate based on passenger gender.
Pair Plot (Age and Fare): A pair plot comparing Age and Fare based on survival status, helping to identify any trends between these numerical features and survival.
Correlation Heatmap: A heatmap displaying correlations among numerical features in the dataset.
Running the Code
To run the code, simply execute each code cell in order if using a Jupyter Notebook or run the script as a Python file. The visualizations will appear inline or in individual pop-up windows.

Data Source
Titanic dataset: Data Science Dojo's Titanic dataset
License
This project is licensed under the MIT License.

Acknowledgments
Data Science Dojo for the Titanic dataset.
Seaborn and Matplotlib for the data visualization tools.
