# Explanatory and Exploratory Data Analysis

Implemented Univariate, Bivariate, and Multivariate Analyses to provide foundational insights
which are crucial for feature identification and manipulation in Feature Engineering and subsequently
inform the selection and preparation of features for Ensemble Methods.

## Explanatory Data Analysis

involves:

- **Univariate Analysis**: Examining the distribution of individual variables.
- **Bivariate Analysis**: Exploring relationships between two variables.
- **Multivariate Analysis**: Investigating interactions between multiple variables.

### Univariate Analysis

Univariate analysis involves examining the distribution and characteristics of individual variables. Techniques used include:

**Histograms**: Used to visualize the distribution of a single variable.

**Box Plots**: Used to display the distribution of a variable and identify outliers.

**Descriptive Statistics**: Calculations such as mean, median, mode, standard deviation, and variance to summarize the central tendency and dispersion of the data.

### Bivariate Analysis

Bivariate analysis examines the relationship between two variables. Techniques used include:

**Scatter Plots**: Used to visualize the relationship between two continuous variables.

**Correlation Coefficients**: Measures the strength and direction of the linear relationship between two variables.

**Heatmaps**: Used to visualize the correlation matrix, showing the correlation coefficients between multiple pairs of variables.

**Box Plots**: Used to compare the distribution of a continuous variable across different categories of a categorical variable.

### Multivariate Analysis

Multivariate analysis involves examining the interactions between multiple variables. Techniques used include:

**Principal Component Analysis (PCA)**: A dimensionality reduction technique that transforms the data into a set of orthogonal components, capturing the maximum variance in the data.

**Parallel Coordinates Plot**: Used to visualize high-dimensional data by plotting each variable on a separate axis and connecting the data points with lines.

**Pair Plots**: Used to visualize pairwise relationships between multiple variables in a dataset.

**Libraries and Functions Used:**
**Pandas**: For data manipulation and analysis.
**NumPy**: For numerical operations.
**Matplotlib**: For creating static visualizations.
**Seaborn**: For creating attractive and informative statistical graphics.
**Plotly Express**: For creating interactive visualizations.
**Scikit-learn**: For machine learning techniques such as PCA and data preprocessing (e.g., StandardScaler, MinMaxScaler).

## Exploratory Data Analysis

Exploratory Data Analysis focuses on discovering patterns, spotting anomalies, and testing hypotheses. Techniques used include:

### Uses the Same techniques as the Explanatory DA

Used another dataset, `YourData.csv`, to perform the exploratory analysis.

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
