
# Chess Games Dataset Analysis

This project performs a comprehensive analysis of a chess games dataset. It covers dataset exploration, cleaning, and various statistical analyses, including univariate, bivariate, and multivariate analyses.

---

## Requirements
To run this project, ensure you have the following libraries installed:
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `scipy`

Install them via:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn scipy
```

---

## How to Run
1. Place the `chess_games.csv` file in the working directory.
2. Copy the `main` function and the accompanying code into a Python file or Jupyter Notebook.
3. Execute the script to analyze the dataset.

---

## Functions Overview

### `load_and_explore_dataset(file_path)`
- **Purpose**: Loads the dataset and provides an overview.
- **Outputs**:
  - Dimensions
  - Summary statistics
  - Data types
  - Missing value analysis
  - Unique value counts

---

### `data_cleaning(df)`
- **Purpose**: Cleans the dataset.
- **Steps**:
  - Fills missing numerical values with the median.
  - Fills missing categorical values with the mode.
  - Removes duplicate rows.

---

### `univariate_analysis(df)`
- **Purpose**: Visualizes the distribution of numerical columns.
- **Visualizations**:
  - Histograms
  - Box plots

---

### `bivariate_analysis(df)`
- **Purpose**: Explores relationships between numerical variables.
- **Visualizations**:
  - Correlation heatmap
  - Scatter plot matrix

---

### `multivariate_analysis(df)`
- **Purpose**: Performs advanced analysis using Principal Component Analysis (PCA).
- **Output**:
  - Explained variance ratio plot for PCA components.

---

## Output
This script generates plots and statistical summaries to provide insights into the dataset.

---

## Dataset
The dataset used in this analysis contains chess game details, including:
- Player ratings
- Number of turns
- Game outcomes
- Opening moves and variations

---

## License
This project is open-source under the MIT License. Feel free to use and modify it.
