# IBM Data Science Capstone Project: SpaceX Falcon 9 First Stage Landing Prediction

## Overview

This project aims to predict the success of SpaceX Falcon 9 rocket first stage landings. If the first stage of the Falcon 9 rocket can be successfully landed, it can be reused for future launches, significantly reducing the cost of access to space. This capability is pivotal for making space travel more economical and sustainable. The project leverages data collected from SpaceX about Falcon 9 launches, including launch site, payload mass, orbit type, and landing outcomes, to create a predictive model that estimates the likelihood of successful landings.

## Project Goals

The primary objectives of this project are:
- To perform extensive data collection, wrangling, and cleaning to prepare the dataset for analysis.
- To conduct exploratory data analysis (EDA) to uncover patterns and insights from the launch history of Falcon 9.
- To utilize interactive visual analytics tools such as Folium for mapping launch sites and Plotly Dash for interactive data visualization.
- To apply machine learning classification models to predict the outcomes of Falcon 9 first stage landings based on launch characteristics.
- To evaluate and select the best performing model based on accuracy and reliability for predicting landing successes.

## Repository Contents

This repository contains Jupyter Notebooks that document the various stages of the project, from data collection to model evaluation:

### 1. Data Collection and Wrangling
- **SpaceX API Data Collection.ipynb:** Demonstrates how to collect Falcon 9 launch data using the SpaceX API, including details about launch sites, payloads, and core stages.
- **Web Scraping SpaceX Launch Records.ipynb:** Illustrates how to scrape additional Falcon 9 launch data from Wikipedia to complement the API data.
- **Data Wrangling.ipynb:** Focuses on cleaning and preparing the collected Falcon 9 launch data for analysis. This notebook addresses missing values, data type conversions, and the encoding of categorical variables to ensure the dataset is suitable for exploratory data analysis and machine learning modeling.

### 2. Exploratory Data Analysis (EDA)
- **EDA with Visualization.ipynb:** Explores the cleaned dataset to identify patterns and insights using various visualization techniques.
- **EDA with SQL.ipynb:** Performs SQL queries on the dataset to analyze Falcon 9 launch records and extract specific information.

### 3. Interactive Visual Analytics
- **Interactive Maps with Folium.ipynb:** Uses Folium to create interactive maps that visualize the geographical distribution of Falcon 9 launch sites.
- **spacex_dash_app.py:** Develops an interactive dashboard to explore Falcon 9 launch data dynamically.

### 4. Predictive Analysis (Classification Models)
- **Machine Learning Prediction.ipynb:** Builds and evaluates several machine learning models to predict the success of Falcon 9 first stage landings, selecting the best model based on performance metrics.

## Outcomes

The project successfully demonstrates the application of data science and machine learning techniques to predict Falcon 9 first stage landing outcomes. Through exploratory data analysis, interactive visualization, and predictive modeling, valuable insights were gained into factors influencing landing success. The best performing model provides a tool for estimating the likelihood of successful landings, supporting decision-making processes related to launch planning and cost management.

## How to Use

Each Jupyter Notebook in this repository is self-contained and includes detailed explanations of the steps involved, from data collection to model evaluation. Users interested in replicating the analysis or exploring the Falcon 9 launch data further can follow the notebooks in sequence for a comprehensive understanding of the project.

## License

This project is shared for educational purposes. All data used in this project is sourced from publicly available information.
