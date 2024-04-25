# Kowloon Property Transaction Analysis

## Introduction
This GitHub repository provides a comprehensive analysis of property transactions in Kowloon using data extracted from the 28Hse website. The analysis includes data cleaning, merging with additional datasets, data aggregation, and data visualization. The repository aims to provide insights into property market trends in Kowloon and uncover interesting patterns and relationships within the dataset.

## Repository Structure
1. **Data**: This folder contains the raw data file "hw.csv" that includes property transaction prices in Kowloon from November 2014 to November 2020.

2. **Notebooks**:
   - *01_Data_Cleaning.ipynb*: This notebook focuses on importing and cleaning the data, handling missing values, dropping irrelevant columns, and renaming columns for better understanding. The transaction dates are converted to the datetime data type.
   - *02_Data_Merging.ipynb*: This notebook demonstrates the merging of additional datasets such as unemployment rate, money supply, and inflation with the property transaction data to explore potential correlations and insights.
   - *03_Data_Aggregation.ipynb*: This notebook showcases the creation of two dataframes: one with monthly average unit prices per district and another with monthly average unit prices per estate. Missing data handling techniques are applied to ensure comprehensive insights.
   - *04_Data_Visualization.ipynb*: This notebook focuses on data visualization techniques to illustrate the overall trend of property prices in Kowloon, as well as trends in selected districts and estates.
   - *05_Data_Analysis.ipynb*: This notebook presents the findings and interesting insights derived from the data analysis process, including correlations, patterns, and any significant observations.

3. **Data Files** (Optional): If additional datasets were used for merging, this folder contains the relevant data files in CSV format.

4. **Results**: This folder includes visualizations, charts, and summaries generated from the data analysis process.

5. **README.md**: This file provides an overview of the repository, its structure, and instructions for running the notebooks.

## Usage
To use this repository, follow these steps:
1. Clone the repository to your local machine.
2. Ensure that Python (version 3.x) and the required libraries (e.g., pandas, matplotlib) are installed.
3. Open and run the notebooks in sequential order, following the instructions provided within each notebook.
4. Explore the results folder for visualizations and insights generated from the analysis.
5. Customize and modify the notebooks as needed for further analysis or specific use cases.

## Contributing
Contributions to this repository are welcome. If you have any suggestions, improvements, or additional analyses, please feel free to create a pull request.

## License
This project is licensed under the MIT license. Please see the LICENSE file for more details.

## Acknowledgments
- The data used in this analysis was obtained from the 28Hse website (https://www.28hse.com/en/estate/).
- Additional datasets used for merging (if applicable) are credited in the respective notebooks.
- The analysis and code provided in this repository serve as a starting point for further exploration and research into Kowloon's property market.

## Disclaimer
The analysis and findings presented in this repository are based on the available data and assumptions made during the analysis process. They should be used for informational purposes only and do not guarantee any investment or financial advice. Users are encouraged to conduct their own research and due diligence before making any decisions based on the information provided.

Please refer to the individual notebooks for detailed code implementation and analysis steps.
