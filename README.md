# Animal Crossing Item Price Analysis

_Case study by Donya Garrison_

**GitHub Repository:** [https://github.com/donyasaur/animal-crossing-data-analysis](https://github.com/donyasaur/animal-crossing-data-analysis)

## Overview

This project analyzes the features of items in Animal Crossing: New Horizons that most influence their selling price. Using the Nook Plaza dataset from Kaggle, I performed data cleaning, exploratory data analysis, and feature importance assessment to answer the question: **Which features of items in Animal Crossing most influence their selling price, and what can we learn from exploring this data?**

## Dataset

- [Animal Crossing New Horizons Nook Plaza Dataset](https://www.kaggle.com/datasets/jessicali9530/animal-crossing-new-horizons-nookplaza-dataset)


## How to Run

1. Clone this repository.
2. Download the dataset from Kaggle and place the relevant CSVs in a `data/raw/` directory.
3. Install dependencies:
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn
    ```
4. Open the notebook:
    ```
    jupyter notebook notebooks/01_item_price_analysis.ipynb
    ```
5. Edit the `DATA_PATH` variable in the notebook if needed to match your CSV location.

## Project Structure

- `notebooks/01_item_price_analysis.ipynb` — Main analysis notebook
- `data/raw/` — Place your raw CSV files here

## Key Findings

- The majority of items in Animal Crossing have low to moderate sell prices, with a few high-value outliers.
- Features such as item category, source, and style show clear influence on the selling price.
- Regression analysis identifies which categorical attributes most strongly predict item value.

## Reflections

I completed this project to practice data cleaning, EDA, and simple feature importance modeling. I learned how to explore categorical and numeric influences on item value, and how to visualize insights for a gaming dataset I enjoy. Future work could explore other item types, or build predictive models for in-game economics.

## Contact

Donya Garrison  
[GitHub Profile](https://github.com/donyasaur)
