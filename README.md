Global Sustainable Energy on World Map
======================================

This repository contains a Python script that generates an interactive world map with a slider, showcasing various sustainable energy indicators from the year 2000 to 2020. The data used for this visualization is sourced from the 'global-data-on-sustainable-energy' dataset.

Getting Started
---------------

### Prerequisites

Before running the script, ensure you have the required dependencies installed. You can install them using the following command:

bashCopy code

`pip install pandas numpy matplotlib seaborn plotly`

### Running the Script

Run the script `global_sustainable_energy_map.py` to visualize the global trends in sustainable energy. The script utilizes Plotly for creating an animated choropleth map.


Code Overview
-------------

The Python script `global_sustainable_energy_map.py` uses the following libraries:

-   `pandas`: For data manipulation and analysis.
-   `numpy`: For numerical operations.
-   `matplotlib` and `seaborn`: For data visualization.
-   `plotly`: For creating interactive plots and maps.

The script reads the 'global-data-on-sustainable-energy' dataset, filters the data for each year from 2000 to 2020, and generates an animated world map with a slider. The map displays various sustainable energy indicators for each country.

Customization
-------------

You can customize the script by choosing different columns from the dataset. The available columns for visualization are:

-   Access to electricity (% of population)
-   Access to clean fuels for cooking
-   Renewable energy share in the total final energy consumption (%)
-   Electricity from fossil fuels (TWh)
-   Electricity from nuclear (TWh)
-   Electricity from renewables (TWh)
-   Low-carbon electricity (% electricity)
-   Primary energy consumption per capita (kWh/person)
-   Energy intensity level of primary energy (MJ/$2017 PPP GDP)
-   Value_co2_emissions_kt_by_country
-   Renewables (% equivalent primary energy)
-   Renewable-electricity-generating-capacity-per-capita
-   Financial flows to developing countries (US $)
-   gdp_growth
-   gdp_per_capita

To visualize a specific indicator, simply uncomment the desired column in the `select_col` list.
