# Iris Dataset Analysis

A Python script to perform data loading, cleaning, basic analysis, and visualization on the classic Iris dataset.

## Description

This project demonstrates how to:

- Load the Iris dataset and save it as a CSV file
- Perform data cleaning by handling missing values and duplicates
- Conduct basic statistical analysis grouped by species
- Generate insightful visualizations including line charts, bar charts, histograms, and scatter plots

The script uses popular Python libraries such as `pandas`, `matplotlib`, `seaborn`, and `scikit-learn` to facilitate data analysis and visualization.

## Installation

1. **Clone the repository** (if applicable) or download the `analysis.py` script.

2. **Install required Python packages**:

```bash
pip install pandas matplotlib seaborn scikit-learn
```

3. Ensure you have Python 3.x installed.

## Usage

Run the script directly from the command line:

```bash
python analysis.py
```

### What the script does:

- Creates an `iris.csv` file from the sklearn Iris dataset.
- Loads and explores the dataset.
- Cleans the data by removing missing values and duplicates.
- Prints descriptive statistics and group-wise means.
- Generates and displays four visualizations:
  - Line chart of sepal length for Setosa species
  - Bar chart of average petal length by species
  - Histogram of petal width distribution
  - Scatter plot of sepal length vs. petal length colored by species

### Example output snippets:

```
 - Setup: 'iris.csv' created for the analysis - 

 - Task 1: Loading and Exploring the Dataset - 

Successfully loaded 'iris.csv'.

First 5 rows of the dataset:
   sepal length (cm)  sepal width (cm)  petal length (cm)  petal width (cm) species
0                5.1               3.5                1.4               0.2  setosa
1                4.9               3.0                1.4               0.2  setosa
...

Basic descriptive statistics for numerical columns:

       sepal length (cm)  sepal width (cm)  petal length (cm)  petal width (cm)
count          150.000000        150.000000         150.000000        150.000000
mean             5.843333          3.054000           3.758667          1.198667
...

All visualizations have been generated.
```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Let me know if you want me to generate a LICENSE file or add more details!
