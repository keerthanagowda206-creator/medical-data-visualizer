# Medical Data Visualizer

A freeCodeCamp Data Analysis with Python project.

## What it does

`medical_data_visualizer.py` analyzes medical examination data
(`medical_examination.csv`) using Pandas, Seaborn and Matplotlib:

- Adds an `overweight` column based on BMI
- Normalizes cholesterol and glucose (0 = good, 1 = bad)
- `draw_cat_plot()` draws a categorical plot of the features, split by cardio
- `draw_heat_map()` cleans the data and draws a correlation heat map

## Run

    python main.py

## Requirements

- Python 3
- pandas, numpy, matplotlib, seaborn
