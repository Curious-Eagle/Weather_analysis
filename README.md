# Environmental Air Quality Analysis 🌍💨

This project provides a comprehensive analysis of air quality and its relationship with meteorological data for a chosen location. It uses Python and common data science libraries to process, analyze, and visualize environmental data trends.

The analysis is structured as a Jupyter Notebook, walking through the entire data science pipeline from data generation and cleaning to advanced modeling and visualization.

---

## Features

* **Data Simulation:** Generates realistic sample air quality (PM2.5, PM10, NO₂) and weather (temperature, humidity) data for demonstration.
* **Data Preparation:** Cleans and merges datasets, handling missing values to prepare the data for analysis.
* **Exploratory Data Analysis (EDA):** Creates a rich set of visualizations to uncover patterns, including:
    * Time series plots with rolling averages.
    * Correlation heatmaps.
    * Distribution histograms.
    * Monthly trend box plots.
* **Advanced Analysis:**
    * **Time Series Decomposition** to identify trend, seasonal, and residual components.
    * **Linear Regression** to model the impact of weather variables on pollutant levels.
* **Interactive Mapping:** Uses Folium to plot the average pollution levels on an interactive map of the study area.

---

## How to Use

This project is designed to be run in a Jupyter Notebook environment.

1.  **Prerequisites:** Ensure you have Python installed with the following libraries:
    * `pandas`
    * `numpy`
    * `matplotlib`
    * `seaborn`
    * `scikit-learn`
    * `statsmodels`
    * `folium`

2.  **Installation:** You can install the required packages using pip:
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn statsmodels folium jupyter
    ```

3.  **Run the Notebook:** Launch Jupyter Notebook and open the `.ipynb` file. Run the cells sequentially from top to bottom to execute the analysis pipeline.

---

## Technologies Used

* **Python 3**
* **Pandas** for data manipulation and analysis.
* **NumPy** for numerical operations.
* **Matplotlib & Seaborn** for static data visualizations.
* **Scikit-learn & Statsmodels** for statistical modeling.
* **Folium** for interactive geographic maps.
