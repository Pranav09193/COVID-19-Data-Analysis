# COVID-19 Data Analysis Project

This project analyzes the impact of the COVID-19 pandemic on various countries around the world. It explores factors such as the number of confirmed cases, deaths, stringency index, population, GDP per capita, and the Human Development Index (HDI). The analysis is performed using Python and popular data analysis libraries like Pandas, Plotly, and Plotly Express.

## Data

The project utilizes two datasets:

1. `transformed_data.csv`: This dataset contains information about the COVID-19 cases, deaths, stringency index, population, GDP per capita, and HDI for different countries.
2. `raw_data.csv`: This dataset contains the raw COVID-19 case and death data for different countries.

## Analysis

The analysis covers the following aspects:

1. **Data Preparation**: The datasets are loaded into Pandas dataframes, and preliminary data exploration is performed.
2. **Data Aggregation**: The data is aggregated by country to obtain the total cases, deaths, stringency index, population, and HDI for each country.
3. **Sorting and Filtering**: The aggregated data is sorted based on the total COVID-19 cases, and the top 10 countries with the highest cases are selected for further analysis.
4. **Visualization**:
   - Bar charts are used to visualize the countries with the highest COVID-19 cases and deaths.
   - A stacked bar chart is created to compare the total cases and deaths for the top 10 countries.
   - A pie chart is used to show the percentage of total cases and deaths.
   - Bar charts are employed to analyze the impact of COVID-19 on the economy by comparing the GDP per capita before and during the pandemic.
   - A bar chart is used to visualize the HDI during the COVID-19 pandemic for the top 10 countries.

## Requirements

To run this project, you need to have the following libraries installed:

- Pandas
- Plotly
- Plotly Express

You can install these libraries using pip:

```
pip install pandas plotly
```

## Usage

1. Clone this repository to your local machine.
2. Navigate to the project directory.
3. Open the Jupyter Notebook or Python script file containing the code.
4. Run the code cells or script to execute the analysis and generate the visualizations.

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.
