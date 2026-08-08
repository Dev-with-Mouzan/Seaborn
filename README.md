<div align="center">

<img src="assets/seaborn-logo.svg" alt="Seaborn" width="220">

# Data Visualization with Seaborn

*A hands-on collection of Jupyter notebooks for mastering statistical data visualization with [Seaborn](https://seaborn.pydata.org/)*

![Python](https://img.shields.io/badge/Python-3.8%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-0.13.x-4C72B0?style=for-the-badge)
![pandas](https://img.shields.io/badge/pandas-2.x-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Contributions](https://img.shields.io/badge/Contributions-Welcome-brightgreen?style=for-the-badge)

</div>

---

## About

This repository is a practical, notebook-driven guide to **statistical data visualization with Seaborn**. Each plot type lives in its own folder, paired with a `usages.ipynb` notebook that explains **when** to reach for that chart — so you learn not just *how* to draw a plot, but *why* you would choose it.

## Features

- **Plot-focused folders** — one folder per plot type, each fully self-contained.
- **When-to-use guidance** — every folder ships a `usages.ipynb` with 2–3 real-world use cases.
- **Real dataset** — examples are built on the Students Performance in Exams dataset (`00-Data/StudentsPerformance.csv`).
- **Beginner friendly** — notebooks are simple, runnable step-by-step, and easy to remix.

## Tech Stack

<div align="center">

<img src="https://cdn.simpleicons.org/python/3776AB" alt="Python" width="36" height="36" title="Python">
<img src="https://cdn.simpleicons.org/pandas/150458" alt="pandas" width="36" height="36" title="pandas">
<img src="https://cdn.simpleicons.org/jupyter/F37626" alt="Jupyter" width="36" height="36" title="Jupyter">
<img src="assets/icons/seaborn.svg" alt="Seaborn" width="36" height="36" title="Seaborn">

</div>

| Tool | Purpose |
| ---- | ------- |
| [Python](https://www.python.org/) | Core programming language |
| [Seaborn](https://seaborn.pydata.org/) | Statistical data visualization |
| [pandas](https://pandas.pydata.org/) | Data loading and manipulation |
| [Jupyter Notebook](https://jupyter.org/) | Interactive development environment |

## Project Structure

```
Seaborn/
├── 00-Data/
│   └── StudentsPerformance.csv     # Students Performance in Exams dataset
├── 01-Bar_plot/
│   ├── Bar_plot.ipynb              # bar chart example
│   └── usages.ipynb                # when to use bar charts
├── 02-Box_plot/
│   ├── Box_plot.ipynb              # box plot example
│   └── usages.ipynb
├── 03-Cat_plot/
│   ├── Cat_plot.ipynb              # sns.catplot example
│   └── usages.ipynb
├── 04-Count_plot/
│   ├── Count_plot.ipynb            # count plot example
│   └── usages.ipynb
├── 05-HeatMap/
│   ├── HeatMap.ipynb               # heatmap example
│   └── usages.ipynb
├── 06-Histogram/
│   ├── Histogram.ipynb             # histogram example
│   └── usages.ipynb
├── 07-Line_plot/
│   ├── Line_plot.ipynb             # line plot example
│   └── usages.ipynb
├── 08-Multiplot/
│   ├── Multiplot.ipynb             # FacetGrid example
│   └── usages.ipynb
├── 09-Pair_plot/
│   ├── Pair_plot.ipynb             # pair plot example
│   └── usages.ipynb
├── 10-Scatter_plot/
│   ├── Scatter_plot.ipynb          # scatter plot example
│   └── usages.ipynb
├── 11-Strip_plot/
│   ├── Strip_plot.ipynb            # strip plot example
│   └── usages.ipynb
├── assets/
│   ├── seaborn-logo.svg            # project logo
│   └── icons/
│       └── seaborn.svg             # Seaborn icon
├── README.md
└── requirement.txt
```

## Plot Types at a Glance

| Folder | Plot | Typical use |
| --- | --- | --- |
| `01-Bar_plot/` | Bar plots | Comparing averages across categories with error bars. |
| `02-Box_plot/` | Box plots | Statistical summaries and detecting outliers per group. |
| `03-Cat_plot/` | Categorical plots | Flexible strip, swarm, box, violin and bar comparisons. |
| `04-Count_plot/` | Count plots | Counting observations in each category. |
| `05-HeatMap/` | Heat maps | Visualizing correlation matrices and grid data. |
| `06-Histogram/` | Histograms | Understanding the distribution of a continuous variable. |
| `07-Line_plot/` | Line plots | Showing trends over time or another continuous variable. |
| `08-Multiplot/` | FacetGrid | Small-multiples comparisons across data subsets. |
| `09-Pair_plot/` | Pair plots | Pairwise relationships between numeric columns. |
| `10-Scatter_plot/` | Scatter plots | Relationships between two numerical variables. |
| `11-Strip_plot/` | Strip plots | Every observation per category with jitter. |

## Prerequisites & Installation

Ensure you have the following installed:

- Python 3.8+
- Jupyter Notebook

Install the required libraries using the commands in [`requirement.txt`](requirement.txt):

```bash
pip install -r requirement.txt
```

or simply:

```bash
pip install pandas seaborn
```

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/Dev-with-Mouzan/Seaborn.git
   ```

2. Enter the project folder:

   ```bash
   cd Seaborn
   ```

3. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

4. Open any plot folder (e.g., `01-Bar_plot/`) and run its notebook. Each folder's `usages.ipynb` explains when that plot type is best applied.

## Contributing

Contributions are welcome. Feel free to open an [issue](https://github.com/Dev-with-Mouzan/Seaborn/issues) or submit a pull request — adding a new plot type folder or improving an existing notebook is a great way to contribute.
