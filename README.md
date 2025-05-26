# Explanatory and Exploratory Data Analysis Project

This project demonstrates the process of understanding and preparing data for machine learning through **Explanatory Data Analysis (EDA)** and **Exploratory Data Analysis (EDA)**. It includes code and documentation for univariate, bivariate, and multivariate analyses.

---

## Table of Contents

- [Project Overview](#project-overview)
- [Project Structure](#project-structure)
- [Explanatory Data Analysis](#explanatory-data-analysis)
  - [Univariate Analysis](#univariate-analysis)
  - [Bivariate Analysis](#bivariate-analysis)
  - [Multivariate Analysis](#multivariate-analysis)
- [Exploratory Data Analysis](#exploratory-data-analysis)
  - [Univariate Analysis](#exploratory-univariate-analysis)
  - [Bivariate Analysis](#exploratory-bivariate-analysis)
  - [Multivariate Analysis](#exploratory-multivariate-analysis)
- [Libraries Used](#libraries-used)
- [How to Run](#how-to-run)
- [License](#license)

---

## Project Overview

The goal of this project is to provide a comprehensive workflow for analyzing and preparing data for machine learning tasks. The workflow is divided into two main parts:

- **Explanatory Data Analysis**: Focuses on summarizing the main characteristics of the data, often with visual methods, to explain what is in the dataset.
- **Exploratory Data Analysis**: Focuses on discovering patterns, relationships, and anomalies in the data, often as a precursor to building predictive models.

---

## Project Structure

- `Explanatory_DA.ipynb`: Jupyter notebook for Explanatory Data Analysis.
- `Exploratory_DA_.ipynb`: Jupyter notebook for Exploratory Data Analysis.
- `README.md`: This documentation file.
- `YourData.csv`: Example dataset used in the notebooks.

---

## Explanatory Data Analysis

Explanatory Data Analysis is about understanding the dataset’s structure and main features. It is divided into:

### Univariate Analysis

Examines each variable individually to understand its distribution and properties.

**Techniques used:**

- **Histograms**: Visualize the distribution of numerical features.
- **Box Plots**: Identify outliers and visualize spread.
- **Descriptive Statistics**: Mean, median, standard deviation, min, max, skewness, kurtosis.
- **Pie Charts & Count Plots**: For categorical variables (e.g., smoking status).

### Bivariate Analysis

Examines relationships between two variables.

**Techniques used:**

- **Scatter Plots**: Visualize relationships between pairs of numerical variables.
- **Box Plots**: Compare distributions across categories.
- **Correlation Matrix & Heatmaps**: Quantify and visualize linear relationships between variables.
- **Joint Plots**: Combine scatter plots and histograms for two variables.

### Multivariate Analysis

Examines interactions among more than two variables.

**Techniques used:**

- **Pair Plots**: Visualize pairwise relationships for multiple variables.
- **Principal Component Analysis (PCA)**: Reduce dimensionality and visualize main variance directions.
- **Parallel Coordinates Plot**: Visualize high-dimensional data.

---

## Exploratory Data Analysis

Exploratory Data Analysis is about discovering patterns, testing hypotheses, and finding anomalies.

### Exploratory Univariate Analysis

- **Histograms** and **Box Plots** for each numerical feature.
- **Descriptive Statistics** for all features.
- **Pie Charts** and **Count Plots** for categorical variables.

### Exploratory Bivariate Analysis

- **Scatter Plots**: Visualize relationships between features and target (e.g., smoking).
- **Correlation Matrix & Heatmaps**: Identify correlated features.
- **Joint Plots**: Regression and density between pairs of variables.

### Exploratory Multivariate Analysis

- **Pair Plots with Hue**: Visualize how multiple features relate, colored by a categorical variable.
- **3D Scatter Plots**: Visualize relationships among three variables at once.
- **PCA**: Reduce data to two principal components for visualization.
- **Parallel Coordinates Plot**: Compare multiple features across classes.

---

## Libraries Used

- **Pandas**: Data manipulation and analysis.
- **NumPy**: Numerical operations.
- **Matplotlib**: Static visualizations.
- **Seaborn**: Statistical visualizations.
- **Plotly Express**: Interactive visualizations.
- **Scikit-learn**: Machine learning, preprocessing, PCA, feature selection.
- **mpl_toolkits.mplot3d**: 3D plotting.

---

## How to Run

1. Make sure you have Python 3.x installed.
2. Install required libraries:
   ```sh
   pip install pandas numpy matplotlib seaborn plotly scikit-learn
   ```
3. Open the notebooks (`.ipynb` files) in Jupyter Notebook or VS Code.
4. Run the cells step by step to reproduce the analysis.

---

## License

This project is licensed under the MIT License.

---

**Note:**

- Replace `YourData.csv` with your actual dataset if needed.
- The notebooks are modular; you can adapt the code for your own data and analysis needs.
