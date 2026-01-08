# Seaborn Data Visualization Project

## Overview
This repository contains a comprehensive collection of Jupyter Notebooks demonstrating various data visualization techniques using the **Seaborn** library in Python. The project is designed to serve as a reference and learning resource for creating informative and attractive statistical graphics.

The analysis and visualizations are primarily based on the `StudentsPerformance.csv` dataset, exploring relationships between different variables such as gender, race/ethnicity, parental level of education, and test scores.

## Table of Contents
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Project Structure](#project-structure)
- [Dataset](#dataset)
- [Notebooks Description](#notebooks-description)
- [Usage](#usage)
- [License](#license)

## Prerequisites
To run the notebooks in this repository, you will need:
- Python 3.x
- Jupyter Notebook or JupyterLab

## Installation
1. **Clone the repository** (if applicable) or download the project files.
2. **Install the required dependencies**. A `requirement.txt` file is provided. You can install the necessary packages using pip:

   ```bash
   pip install -r requirement.txt
   ```
   
   *Note: The primary dependencies are `pandas` and `seaborn`.*

## Project Structure
```
SEAborn/
├── Data_Set/
│   └── StudentsPerformance.csv  # Dataset used for visualizations
├── NoteBook/                    # Collection of Jupyter Notebooks
│   ├── Cat_plot.ipynb           # Categorical data plots
│   ├── Count_plot.ipynb         # Count plots (histograms for categorical data)
│   ├── bar_plot.ipynb           # Bar charts
│   ├── box_plot.ipynb           # Box plots for distribution analysis
│   ├── heatMap.ipynb            # Heatmaps for correlation matrices etc.
│   ├── histtogram_plot.ipynb    # Histograms for univariate distribution
│   ├── line_plot.ipynb          # Line charts for trends
│   ├── multiplot.ipynb          # Complex layouts (FacetGrid, PairGrid)
│   ├── pair_plot.ipynb          # Pair plots for multivariate analysis
│   ├── scatter_plot.ipynb       # Scatter plots for relationship analysis
│   └── strip.ipynb              # Strip plots
└── requirement.txt              # List of python dependencies
```

## Dataset
This project uses the **Students Performance in Exams** dataset (`StudentsPerformance.csv`).
It includes scores from three exams and a variety of personal, social, and economic factors that have been collected for analysis.

**Columns likely include:**
- Gender
- Race/ethnicity
- Parental level of education
- Lunch
- Test preparation course
- Math score
- Reading score
- Writing score

## Notebooks Description
Here is a brief overview of the notebooks included in the `NoteBook` directory:

| Notebook | Description |
|----------|-------------|
| `Cat_plot.ipynb` | Demonstrates the use of `sns.catplot` to create various categorical plots like strip, swarm, box, violin, etc. |
| `Count_plot.ipynb` | Shows how to visualize the count of observations in each categorical bin using `sns.countplot`. |
| `bar_plot.ipynb` | detailed examples of creating bar plots to aggregate data across categories. |
| `box_plot.ipynb` | Visualizing the distribution of quantitative data with box-and-whisker plots. |
| `heatMap.ipynb` | Visualizing matrix-like data, particularly useful for correlation matrices. |
| `histtogram_plot.ipynb`| plotting univariate or bivariate histograms to show distributions of datasets. |
| `line_plot.ipynb` | visualization of data trends over time or other continuous variables. |
| `multiplot.ipynb` | Advanced plotting techniques to visualize defining subsets of data (likely using FacetGrid). |
| `pair_plot.ipynb` | Plotting pairwise relationships in a dataset. |
| `scatter_plot.ipynb` | displaying values for typically two variables for a set of data to analyze relationships. |
| `strip.ipynb` | Creating strip plots, which are scatter plots where one variable is categorical. |

## Usage
1. Open your terminal or command prompt.
2. Navigate to the project directory:
   ```bash
   cd e:\SEAborn
   ```
3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Navigate to the `NoteBook` folder in the Jupyter interface and open any notebook to view the code and visualizations.

---
*Created by Mouzan Raza*
