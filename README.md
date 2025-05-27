# Real-Estate-Price-Analysis

## Overview

This project analyzes housing data to predict median house prices using machine learning models. It implements Random Forest and Gradient Boosting regression models, evaluates their performance, and identifies the most influential features affecting house prices.

![image](https://github.com/user-attachments/assets/ca253a7e-ae8c-4110-82df-052a27fb0254)


## Features

* **Data Exploration**: Performed exploratory data analysis to understand the distribution and relationships of features.
* **Preprocessing**: Handled missing values, feature scaling, and encoding of categorical variables.
* **Modeling**:

  * Implemented **Random Forest Regressor**
  * Implemented **Gradient Boosting Regressor**
* **Evaluation**:

  * Used **k-fold cross-validation** to assess model stability.
  * Calculated **Mean Squared Error (MSE)** on the test set.
* **Feature Importance**: Trained a Random Forest model to rank features by their influence on median house price.

## Top Influential Features

Based on the Random Forest model, the top three features impacting median house price are:

1. **Median Income**
2. **Proximity to Inland**
3. **Population per Household**

## Files

* `MLCH2.ipynb`: Jupyter notebook containing the full analysis, from data preprocessing to model evaluation and feature importance.
* `.gitignore`: Lists files and directories ignored by Git.
* `LICENSE`: License information for the project.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/akhilesh360/Real-Estate-Price-Analysis.git
   cd Real-Estate-Price-Analysis
   ```
2. Create and activate a virtual environment:

   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows: venv\\Scripts\\activate
   ```
3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Open the notebook:

   ```bash
   jupyter notebook MLCH2.ipynb
   ```
2. Run all cells to reproduce the analysis and view results.

## Results

* The models achieve competitive performance in predicting median house prices, with detailed MSE scores available in the notebook.
* Feature importance analysis highlights the key drivers of housing prices.

## License

This project is licensed under the [MIT License](LICENSE).

## Author

Created by Sai Akhilesh.
