# COVID-19 Global Impact Analysis

## Project Overview
This project analyses the global impact of COVID-19, focusing on three countries: India, the United States, and the United Kingdom.

The project explores COVID-19 cases, deaths, monthly trends, and vaccination data to understand how the pandemic affected these countries.

## Objectives
- Analyse COVID-19 cases and deaths.
- Compare the impact of COVID-19 across three countries.
- Identify monthly trends in new cases and deaths.
- Examine vaccination data.
- Present important findings through charts and visualisations.

## Dataset
**Source:** [Our World in Data – COVID-19 Dataset](https://github.com/owid/covid-19-data)

- Data period: January 2020 to August 2024.
- Original dataset: 429,435 rows and 67 columns.
- Selected dataset: 429,435 rows and 16 columns.
- Cleaned dataset: 421,665 rows and 16 columns.

The dataset was cleaned by selecting relevant columns and removing incomplete duplicate location-date records.

## Technologies Used
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- ReportLab

## Analysis Performed
1. Dataset loading and exploration.
2. Data cleaning and preprocessing.
3. Country-wise COVID-19 statistics.
4. Monthly new cases analysis.
5. Monthly new deaths analysis.
6. Vaccination data comparison.
7. Data visualisation.

## Countries Analysed
- India
- United States
- United Kingdom

## Visualisations
The project includes four charts:

1. COVID-19 Cases per Million
2. Monthly New COVID-19 Cases
3. Monthly New COVID-19 Deaths
4. Fully Vaccinated Population (%)

## Key Findings
- The United States recorded the highest reported cumulative cases and deaths among the three selected countries.
- India experienced its highest monthly new cases and deaths in May 2021.
- The United States and United Kingdom recorded their highest monthly new cases in January 2022.
- Monthly reported deaths generally declined after 2022 across all three countries.

## Project Files
- `covid19_global_data_original.csv` – Original dataset.
- `covid19_global_data_cleaned.csv` – Cleaned dataset.
- `COVID19_Global_Impact_Analysis.ipynb` – Python notebook containing the analysis and charts.
- `COVID19_Executive_Summary.pdf` – One-page project summary.
- `README.md` – Project documentation.

## How to Run the Project
1. Download the project files.
2. Open Google Colab.
3. Upload the Jupyter Notebook.
4. Upload the cleaned CSV dataset.
5. Run the notebook cells in order.
6. View the generated analysis and charts.

## Conclusion
This project provides a comparative analysis of the COVID-19 pandemic in India, the United States, and the United Kingdom. It uses data analysis and visualisation techniques to identify trends and understand the differences in the pandemic's impact.

**Note:** The analysis uses historical reported data available through 14 August 2024. Missing values and reporting differences may affect comparisons.


**Note:** The cleaned dataset is not included in this repository because of its file size. It can be recreated by downloading the original dataset from the Our World in Data source
