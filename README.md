# Car Model Acceptance Using AI/ML Models

## Overview

This project analyzes car model acceptance using multiple machine learning algorithms. It leverages the Car Evaluation dataset from the UCI Machine Learning Repository to classify cars based on factors like price, maintenance, safety, and other essential attributes. The goal is to build and compare ML models to distinguish acceptable and unacceptable car models and support decision-making for buyers.

## Table of Contents

- [About the Project](#about-the-project)
- [Dataset](#dataset)
- [Installation](#installation)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Results](#results)
- [References](#references)
- [License](#license)

## About the Project

First-time car buyers and those unfamiliar with the automobile industry often struggle to choose the right car. This project uses various machine learning methods to help classify car models and provide recommendations. The following classifiers were applied:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Random Forest
- Decision Tree

## Dataset

- **Source:** [UCI Car Evaluation Dataset](https://archive.ics.uci.edu/ml/datasets/car+evaluation)
- **Features:** buying, maint, doors, persons, lug_boot, safety
- **Target:** class (unacc, acc, good, vgood)
- **Instances:** 1,728

## Installation

1. Clone this repository:
    ```
    git clone https://github.com/Ngawang04/Car-Model-Acceptance-using-AI-ML.git
    ```
2. Install necessary Python packages (preferably in a virtual environment):
    ```
    pip install -r requirements.txt
    ```

## Project Structure


## Usage

1. **Preprocessing:**  
   The dataset is loaded and processed; categorical variables are split and checked for missing values.

2. **Exploratory Data Analysis:**  
   Key features and class distributions are visualized.

3. **Model Training:**  
   Four classifiers (Logistic Regression, KNN, Random Forest, Decision Tree) are trained and compared.

4. **Evaluation:**  
   Model results compared for accuracy and F1-score. Methods like SMOTE are used for class imbalance.

**To run:**

Open and run all cells in `analysis_notebook.ipynb` or execute the main script:


## Results

| Model                | Accuracy |
|----------------------|----------|
| Logistic Regression  | 71%      |
| K-Nearest Neighbors  | 92%      |
| Random Forest        | 99%      |
| Decision Tree        | 79%      |

**Random Forest performed best on this dataset.**

## References

- Fatalla, R., “Decision Model for Car Evaluation Final Project in Pattern Recognition”.
- [UCI ML Repository - Car Evaluation Dataset](https://archive.ics.uci.edu/ml/datasets/car+evaluation)
- [ProjectPro: Compare scikit-learn classifiers](https://www.projectpro.io/recipes/compare-sklearn-classification-algorithms-in-python)
- See project report for full references.

## License

This project is licensed under the [MIT License](LICENSE).
