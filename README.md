# Exploratory Data Analysis and Summary Statistics in R

This repository contains the starter Quarto file for Homework 1, focused on performing foundational exploratory data analysis (EDA) and numerical summarization techniques using R. The document walks through data inspection, transformation, visualization, and interpretation using a real dataset.

## Objective

To demonstrate proficiency in:

- Reading and preparing real-world data in R
- Applying statistical summaries and exploratory techniques
- Leveraging visualization for feature exploration and insight generation
- Comparing patterns across categorical and numerical variables

The assignment emphasizes reproducible workflows using Quarto and the `tidyverse` for structured, readable analytics.

## Technologies Used

- **R**: Core programming language for statistical computing
- **Quarto**: Literate programming tool for combining code, outputs, and narrative
- **Tidyverse**:
  - `dplyr` for data manipulation
  - `ggplot2` for data visualization
  - `readr` / `readxl` for data import

## Key Topics Covered

### Data Loading and Inspection

- Use of `read_csv()` or `read_excel()` to load structured datasets
- Column type validation, missing data detection, and descriptive inspection using:
  - `glimpse()`
  - `summary()`
  - `table()` and `n_distinct()`

### Feature Engineering

- Creation of new features using `mutate()` for categorization and transformation
- Type conversions with `as.numeric()` and `as.factor()`
- Use of `case_when()` to simplify multi-conditional logic

### Summary Statistics

- Group-wise summaries using `group_by()` and `summarise()`
- Calculation of mean, median, standard deviation, and interquartile range (IQR)
- Generation of frequency tables and cross-tabulations

### Exploratory Data Visualization

- Construction of:
  - Bar charts for categorical distribution
  - Boxplots for conditional distribution comparisons
  - Histograms and density plots for numeric shape exploration
- Use of `facet_wrap()` for subgroup visualizations

### Interpretation and Insights

- Critical analysis of data distribution and summary outputs
- Comparison of data segments based on domain-specific attributes
- Identification of trends, anomalies, and potential biases

## Deliverables

- A complete `.qmd` file demonstrating:
  - Clean, commented R code
  - Interpretive markdown narrative
  - Embedded plots and outputs
- Structured sections for:
  - Data prep
  - Feature evaluation
  - Summary insight generation

## Usage

1. Clone or download the repository.
2. Open the `.qmd` file in RStudio.
3. Install dependencies if needed:
   ```r
   install.packages("tidyverse")
