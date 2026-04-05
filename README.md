# GDP vs Life Expectancy

Python data analysis project exploring how GDP and life expectancy move together across six countries between 2000 and 2015.

## Project focus

This repository looks at the relationship between economic output and public health outcomes by comparing:

- GDP trends over time
- life expectancy trends over time
- cross-country differences in scale and trajectory
- the usefulness of log-scaling GDP for clearer visual comparison

## Countries in the dataset

- Chile
- China
- Germany
- Mexico
- United States of America
- Zimbabwe

The dataset contains 96 rows covering the years 2000 through 2015.

## Tech

- Python
- pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Repo layout

- `Life-Expectancy-and-GDP/life_expectancy_gdp.ipynb` - the main notebook
- `Life-Expectancy-and-GDP/all_data.csv` - source dataset used by the notebook

## Run locally

```bash
cd Life-Expectancy-and-GDP
jupyter notebook life_expectancy_gdp.ipynb
```

## Why this repo is in the portfolio

This project is a good example of notebook-based exploratory analysis: start with a question, clean the data, visualize the patterns, and use the visuals to explain how countries differ instead of treating the dataset as a single blended average.
