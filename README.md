# Earnings Predictions for College Graduates

## Overview

This project utilizes a Jupyter Notebook to analyze a dataset provided by the American Community Survey and FiveThirtyEight, featuring 174 unique college majors and their characteristics such as unemployment rates and major categories. The focus is on understanding the relationship between college majors, gender, and earnings, particularly highlighting the impact of the gender wage gap on newly graduated job market.

## Key Findings

- The model predicts a starting median earning of $89,363 for a Data Science major in California after adjusting for inflation and cost of living.
- An average entry-level Data Scientist's salary ranges between $80,000 and $90,000 according to Springboard.com.
- The application of machine learning paradigms uncovers significant relationships between college major types, gender, and overall income, emphasizing the gender wage gap's impact.
- In the Random Forest Classifier utilised in the model, the 1st and 3rd features with the highest relative importance were 'ShareWomen' and 'Women.'
- For more detailed findings, please consult the Jupyter Notebook or the slides which contain further visualizations and explanations.

## Dataset

The dataset comprises 174 rows and 21 columns, sourced from the American Community Survey and FiveThirtyEight. Each row represents a distinct college major and includes various metrics such as unemployment rate and major category.

## Requirements

To run this notebook, you'll need Python 3 and the following libraries:
- pandas
- scikit-learn
- matplotlib
- seaborn

You can install these packages using pip:

```bash
pip install pandas scikit-learn matplotlib seaborn
```

## Usage

1. Clone the repository to your local machine.
2. Ensure you have the required libraries installed.
3. Run the Jupyter Notebook to see the analysis and the results.
4. You can modify the `new_major_data` dictionary in the notebook to predict earnings for different majors.


## Acknowledgments

- American Community Survey and FiveThirtyEight for providing the dataset.
- Springboard.com for additional salary information.
