# Data Visualization of Psychological Disorders through Machine Learning

Welcome to the "Data Visualization of Psychological Disorders through Machine Learning" project. This project aims to analyze and visualize human behavior based on health reports, sleep habits, alcohol consumption, and personal and professional life factors. The dataset is sourced from the CDC National Health and Examination Survey.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Machine Learning Algorithms](#machine-learning-algorithms)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Results](#results)
- [Technologies Used](#technologies-used)
- [Acknowledgments](#acknowledgments)
- [License](#license)

## Introduction

The project focuses on understanding and predicting psychological disorders by utilizing machine learning algorithms. By combining data from various sources, including health reports, sleep habits, and personal/professional life details, the goal is to determine the most frequent causes of suicide.

## Dataset

The dataset used in this project is obtained from the CDC National Health and Examination Survey. It includes the following CSV files:
- `xtrain.csv`: Training data features
- `ytrain.csv`: Training data labels
- `xtest.csv`: Testing data features
- `ytest.csv`: Testing data labels
- `fulldata.csv`: Comprehensive dataset combining training and testing data

## Machine Learning Algorithms

The following machine learning algorithms are employed in this project:
- Regression
- Clustering
- Support Vector Machine (SVM)
- Stochastic Gradient Descent
- Confusion Matrix
- One-Hot Encoder
- Soft Encoder

## Project Structure

The project is organized as follows:
- `src/`: Contains the source code for machine learning algorithms and data analysis.
- `data/`: Stores the dataset files (`xtrain.csv`, `ytrain.csv`, `xtest.csv`, `ytest.csv`, `fulldata.csv`).
- `results/`: Holds the results obtained from different modes and the final combined result.

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/SaiHimaja24/Data-Visualization-of-Psychological-Disorder-of-a-Human-through-Machine-Learning.git
Navigate to the project folder:

'''bash
Copy code
cd Data-Visualization-of-Psychological-Disorder-of-a-Human-through-Machine-Learning

Run the machine learning algorithms and analysis scripts.

Results
The results are stored in the results/ directory. After combining all the results, the final outcome, i.e., the most frequent cause of suicide, is displayed.

Technologies Used
The project is developed using the following technologies:

Python
Machine Learning Libraries (Scikit-learn, TensorFlow, etc.)
Pandas
NumPy
Matplotlib
Jupyter Notebooks

Acknowledgments

The dataset is sourced from the CDC National Health and Examination Survey
