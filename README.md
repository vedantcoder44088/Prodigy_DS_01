# Prodigy_DS_01

# Data Analysis and Visualization with Python

This repository contains a Python script for data analysis and visualization tasks performed on a dataset. The script demonstrates various data exploration techniques and visualization methods using popular libraries such as pandas, numpy, matplotlib, and seaborn.

## Getting Started

To get started, follow these instructions:

1. Clone the repository to your local machine:

```
git clone https://github.com/vedantcoder44088/Prodigy_DS_01.git
```

2. Navigate to the project directory:

```
cd Prodigy_DS_01
```

3. Ensure you have Python and the required libraries installed. You can install them using pip:

```
pip install pandas numpy matplotlib seaborn
```

4. Download the dataset named "data.csv" and place it in the project directory.

## Exploratory Data Analysis (EDA)

The Python script `Prodigy_DS_01.ipynb` contains the following steps for EDA:

- **Loading Data**: The script loads the dataset into a pandas DataFrame for further analysis.
  
- **Data Exploration**: It explores the dataset by displaying its structure, including its shape, columns, and information.

- **Data Cleaning**: Missing values are handled by forward filling (`method="ffill"`).

- **Data Analysis**:
  - Unique values of certain columns like "Country Name", "Country Code", "Indicator Name", and "Indicator Code" are extracted.
  - Unnecessary columns like "Indicator Name", "Indicator Code", and "Country Code" are dropped from the DataFrame.

- **Visualization**:
  - Histograms are used to visualize the distribution of values for each year.
  - A horizontal bar chart is plotted to display the total values per year.
  - The top 10 countries with the least values in 1960 and 2022 are identified and visualized using seaborn barplots.

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn

## Usage

- Open the Jupyter Notebook `analysis_visualization.ipynb` to view the analysis script.
- Run each cell of the notebook to execute the code and visualize the results.

----
