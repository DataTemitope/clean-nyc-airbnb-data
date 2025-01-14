# clean-nyc-airbnb-data
A comprehensive data cleaning project on NYC Airbnb 2019 dataset. This repository contains Python scripts that demonstrate step-by-step data cleaning techniques, including handling missing values, removing special characters, standardizing text, and detecting outliers. 
# NYC Airbnb 2019 Data Cleaning  

This repository contains a Python script for cleaning the 2019 NYC Airbnb dataset. The goal of this project was to transform messy data into a clean, consistent format for analysis.

## Dataset  
The dataset includes 48,895 rows and 16 columns containing information about Airbnb listings in New York City. The cleaning process tackled:  
- Missing values  
- Inconsistent text formatting  
- Outliers in numerical columns  

## Libraries Used  
- **Pandas**: For data manipulation  
- **NumPy**: For numerical operations  
- **Matplotlib** & **Seaborn**: For visualizing data  

## Cleaning Steps  
1. **Loaded the dataset** and inspected its structure.  
2. **Handled missing values**:
    - Filled `name` and `host_name` with "Unknown".  
    - Replaced missing `reviews_per_month` values with `0`.  
    - Converted `last_review` to proper datetime format.  
3. **Standardized text columns** by capitalizing the first letter and removing special characters.  
4. **Detected and flagged outliers** in numerical columns using the Interquartile Range (IQR) method.  

## Code  
The cleaning process is fully documented in `[nyc_airBNBclean.ipynb](https://github.com/DataTemitope/clean-nyc-airbnb-data/blob/main/NYC_airBNBclean.ipynb)`. 
