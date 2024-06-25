# Bengaluru House Data Cleaning and Preprocessing

This repository contains a comprehensive data cleaning and preprocessing project on the Bengaluru House Data dataset. The project includes various data preprocessing techniques such as handling missing values, outlier detection, encoding categorical variables, and normalizing numerical features.

## Dataset

The dataset used in this project is the Bengaluru House Data, which contains information about house prices in Bengaluru. The dataset includes various features such as location, size, total square feet, and price.

## Project Overview

The main steps of the data cleaning and preprocessing process are as follows:

1. **Loading the Data**: The dataset is loaded into a Pandas DataFrame.
2. **Inspecting the Data**: Displaying the first few rows, data types, and basic statistics to understand the dataset.
3. **Handling Missing Values**: Missing values are filled using mean for numerical columns and mode for categorical columns.
4. **Detecting and Handling Outliers**: Outliers are detected using the Z-score method and removed if they exceed a threshold.
5. **Encoding Categorical Variables**: Label encoding is used for categorical variables.
6. **Normalizing Numeric Features**: Numeric features are standardized using `StandardScaler`.
7. **Data Visualization**: A correlation heatmap is created to visualize relationships between features.
8. **Saving the Cleaned Data**: The cleaned dataset is saved to a new CSV file for further analysis or modeling.

## Files in the Repository

- **Bengaluru_House_Data.csv**: The original dataset containing information about house prices in Bengaluru.
- **code.ipynb**: Jupyter Notebook containing the detailed implementation of data cleaning and preprocessing steps.
- **cleaned_Bengaluru_House_Data.csv**: The cleaned and preprocessed dataset saved after applying all the data cleaning techniques.

## Usage

To run the code and reproduce the data cleaning steps, follow these instructions:

1. Clone the repository:
   ```sh
   git clone https://github.com/aliibraheem516/bengaluru-house-data-cleaning.git
   cd bengaluru-house-data-cleaning
