# Air Quality Analysis Project: Dingling Station

## Project Overview
Submission for Dicoding "Learn Data Analysis with Python" course. This dashboard provides an interactive way to explore air quality data, specifically focusing on PM2.5 levels and their effect on the climate.

## Table of Contents
- [Data Source](#data-source)
- [Libraries Used](#libraries-used)
- [Key Insights](#key-insights)
- [How to Run the Dashboard](#how-to-run-the-dashboard)
- [About Me](#about-me)
- [Credit](#credit)

## Data Source
The dataset used in this project includes air quality measurements from the Dingling station, with a focus on PM2.5 levels and other related environmental data.

## Libraries Used
- Streamlit
- Pandas
- Matplotlib
- Seaborn
- NumPy
- SciPy
- Statsmodels

## Key Insights
- Seasonal variation in PM2.5 levels with higher concentrations in colder months.
- Correlation between PM2.5 levels and weather conditions like temperature and humidity.
- Trends and patterns of PM2.5 revealed through time series analysis.

## How to Run the Dashboard

To run the Air Quality Analysis Dashboard, follow these steps:

### Setup Environment

1. **Create and Activate a Python Environment**:
   - If using Conda (ensure [Conda](https://docs.conda.io/en/latest/) is installed):
     ```
     conda create --name airquality-ds python=3.9
     conda activate airquality-ds
     ```
   - If using venv (standard Python environment tool):
     ```
     python -m venv airquality-ds
     source airquality-ds/bin/activate  # On Windows use `airquality-ds\Scripts\activate`
     ```

2. **Install Required Packages**:
   - The following packages are necessary for running the analysis and the dashboard:
     ```
     pip install pandas numpy scipy matplotlib seaborn streamlit statsmodels
     ```

     or you can do
     ```
     pip install -r requirements.txt
     ```
### Run the Streamlit App

1. **Navigate to the Project Directory** where `dashboard.py` is located.

2. **Run the Streamlit App**:
    ```
    streamlit run dashboard.py
    ```

### Additional Files

- The dataset used for this analysis is included in the project repository.
- A detailed Python notebook (`Dingling_AQI_Visualization.ipynb`) containing the data analysis and visualizations is also provided.
---
### P.S.

Since Dicoding recommended creating the good and tidy folder structures, as `dashboard.py` in `dashboard` folder, then the deployment for Streamlit App affected.

That was why I put the `requirements.txt` in the `dashboard` folder as well.  

---

## About Me
- **Name**: William Heria Chandra
- **Email Address**: nbwilliam.hc@gmail.com
- **Dicoding ID**: [william_hc](https://www.dicoding.com/users/william_hc/)

## Credit
Big thanks to
- **Name**: Reza Maliki Akbar
- **Email Address**: rezamaliki.akbar@gmail.com
- **Dicoding ID**: [maliki_borneo](https://www.dicoding.com/users/maliki_borneo/)

for his help on his project
