# Water-Quality-Test
The Water Quality Test Project predicts water potability using machine learning models. It analyzes features like pH, hardness, and turbidity. Steps include data cleaning, exploratory analysis, model training, and evaluation. Logistic Regression and XGBoost achieved up to 86% accuracy, optimizing safe water predictions.

This project predicts water potability using machine learning. By analyzing water properties like pH, hardness, and turbidity, it determines whether water is safe to drink.

## Overview

The project involves:
- **Data Cleaning**: Handling missing values and outliers.
- **EDA**: Visualizing data distributions and relationships.
- **Model Training**: Using Logistic Regression, Decision Tree, and XGBoost.
- **Evaluation**: Comparing models based on accuracy and F1-score.

## Dataset

The dataset, `water_potability.csv`, includes key water quality parameters. After preprocessing, models were trained to classify water as potable or not.

## Results

- **XGBoost** achieved the best performance with 86% training accuracy and 65% test accuracy.
- Logistic Regression performed well for simpler use cases.




## How to Run the Project
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Jiyachahal/Water-Quality-Test.git
2. **Open and Run the Jupyter Notebook:**
    [View the Jupyter Notebook](./code.ipynb)
   
## Key Files
- code.ipynb: Contains the entire workflow, including preprocessing, modeling, and evaluation.
- water_potability.csv: Dataset used for analysis.

## Dependencies
- Python 3.x
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- XGBoost

## Contributions 
Contributions are welcome. Fork the repo, make updates, and submit a pull request.
