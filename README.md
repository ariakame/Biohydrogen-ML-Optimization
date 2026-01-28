# Optimizing Fermentative Biohydrogen Yield: A Machine Learning Approach

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1cDveA7pLBJ3PrY8Xxy48hjZsC8yujTFh?authuser=1)

## Project Overview
This project presents a data-driven framework to predict and optimize biohydrogen production via dark fermentation. Using a novel dataset curated from 40+ peer-reviewed studies, we developed a machine learning model capable of mapping complex, non-linear interactions between substrate properties and environmental factors.

## Key Features
* **Novel Dataset:** A harmonized database involving unit standardization (STP), stoichiometric hexose equivalents, and COD normalization.
* **Top Performing Model:** The **Gradient Boosting Regressor** achieved an **R² of 0.8942**.
* **Error Metrics:** Low MAE (0.31 L H₂/L/day) and RMSE (0.42 L H₂/L/day).

## Technical Stack
* **Language:** Python
* **Environment:** Google Colab
* **Libraries:** Scikit-Learn, Pandas, NumPy, Matplotlib

## Authors
* **Archith Shankar:** Software development, ML modeling, and dataset construction.
* **Arya K (ariakame):** Biological literature review, data curation, and validation.

## How to use
1. Click the **"Open in Colab"** badge above.
2. Ensure you have access to the shared Google Drive link.
3. Run the cells to see the data preprocessing, model training, and results visualization.
