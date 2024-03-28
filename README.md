# IRIS FLOWER CLASSIFICATION

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Dependencies](#dependencies)
- [Usage](#usage)
- [Results](#results)
- [Future Work](#future-work)

## Introduction
The Iris flower dataset consists of three species: setosa, versicolor, and virginica. The objective of this project is to train a machine learning model that can accurately classify Iris flowers into their respective species based on their sepal and petal measurements.

## Dataset
The Iris dataset contains measurements of sepal length, sepal width, petal length, and petal width for three species of Iris flowers: setosa, versicolor, and virginica.

## Project Structure
- `IRIS TYPE CLASSIFICATION.ipynb`: Jupyter Notebook containing the code for data exploration, preprocessing, model training, and evaluation.
- `IRIS.csv`: CSV file containing the Iris dataset.

## Dependencies
This project requires the following dependencies:
- Python 3.x
- pandas
- NumPy
- sci-kit-learn
- matplotlib
- seaborn

You can install the dependencies using pip:
```bash
pip install pandas NumPy sci-kit-learn matplotlib seaborn
```
## Usage
To run the project:
- Clone this repository to your local machine.
- Open `IRIS TYPE CLASSIFICATION.ipynb` in Jupyter Notebook.
- Run the cells in the notebook sequentially to explore the data, preprocess it, train the machine learning model, and evaluate its performance.

## Results
### Machine Learning Model Results
The trained machine learning model achieves the following performance metrics on the test data:

| Precision | Recall | F1-Score | Support |
|-----------|--------|----------|---------|
| 1.00      | 1.00   | 1.00     | 10      |
| 1.00      | 1.00   | 1.00     | 9       |
| 1.00      | 1.00   | 1.00     | 11      |

- Accuracy: 1.0
- Macro Avg: 1.00 1.00 1.00 30
- Weighted Avg: 1.00 1.00 1.00 30

### Cross-Validation Results
- Cross-validation scores: [0.96666667 0.96666667 0.93333333 0.96666667 1. ]
- Mean accuracy: 0.9667
- Standard deviation of accuracy: 0.0211

## Future Work
Potential future work for this project includes:
- Experimenting with different machine learning algorithms and hyperparameters.
- Exploring additional features or techniques for improving model performance.
- Deploying the trained model in a real-world application.
