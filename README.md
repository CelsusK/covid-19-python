# COVID-19 Global Data Tracker

## Project Description

This project analyzes global COVID-19 trends using real-world data. It focuses on tracking cases, deaths, recoveries (if available in the dataset), and vaccinations across different countries and over time. The analysis involves data cleaning, exploratory data analysis (EDA), visualization of trends, and communication of key insights through a Jupyter Notebook.

## Project Objectives

* **Data Import and Cleaning:** Load and preprocess the global COVID-19 dataset using pandas.
* **Time Series Analysis:** Analyze trends in cases, deaths, and vaccinations over time for selected countries.
* **Cross-Country Comparison:** Compare key COVID-19 metrics across different countries and regions.
* **Data Visualization:** Visualize trends and comparisons using various charts (line plots, bar charts) and potentially geographical maps.
* **Reporting:** Communicate the data analysis process, findings, and insights in a clear and concise manner within a Jupyter Notebook or a PDF report.

## Project Structure

The project is organized as follows:

1.  **`data/`:** (Optional) This directory might contain the raw data file (`owid-covid-data.csv`) if you choose to include it in your repository (be mindful of data update frequency and potential size).
2.  **`reports/`:** (Optional) This directory could contain the final report in PDF format or other output formats.
3.  **`README.md`:** The current file, providing an overview of the project.

## Setup and Usage

1.  **Prerequisites:**
    * Python 3.x
    * Jupyter Notebook (or VS Code with Jupyter extension)
    * pandas (`pip install pandas`)
    * matplotlib (`pip install matplotlib`)
    * seaborn (`pip install seaborn`)
    * plotly express (optional for interactive maps: `pip install plotly`)

2.  **Data Acquisition:**
    * Download the `owid-covid-data.csv` file from the Our World in Data website: [https://ourworldindata.org/covid-cases](https://ourworldindata.org/covid-cases)
    * Save the downloaded file in the same directory as your Jupyter Notebook or in a `data/` subdirectory.

3.  **Running the Analysis:**
    * Navigate to the `notebooks/` directory (or the directory where you saved the notebook).
    * Open the `covid_data_tracker.ipynb` file using Jupyter Notebook.
    * Follow the steps within the notebook to load, clean, analyze, and visualize the data.
    * The notebook contains code cells for performing the analysis and markdown cells for explanations and insights.

## Key Findings (To be populated after running the analysis)

* In the Percentage of people vaccinated over time graph, there was a huge drop of No. of people vaccinated in the United States as of 2022-01.
* Afghanistan had an incline in Total vaccinations and overtook United States.
* As of 2023 and 2024 there were no new cases

## Visualizations (Examples of what to expect)

* Line charts showing the trend of total COVID-19 cases over time for selected countries.
* Line charts illustrating the trend of total deaths over time for selected countries.
* Line charts comparing the daily new COVID-19 cases between different countries.
* Bar charts comparing total cases or deaths across a set of countries.
* Line charts showing the progress of vaccination campaigns (total vaccinations) over time.
* (Optional) Choropleth map visualizing the global distribution of COVID-19 cases or vaccination rates.

## Contributing

Contributions to this project are welcome. Feel free to fork the repository, make changes, and submit a pull request.

## Acknowledgements

* Our World in Data for providing the comprehensive COVID-19 dataset.
* The developers of pandas, matplotlib, seaborn, and plotly for their excellent data analysis and visualization libraries.
