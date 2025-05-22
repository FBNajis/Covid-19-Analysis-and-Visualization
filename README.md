# COVID-19 Data Analysis and Visualization

**Author:** Umar Khairur Rahman

---

## Table of Contents
- [COVID-19 Data Analysis and Visualization](#covid-19-data-analysis-and-visualization)
  - [Table of Contents](#table-of-contents)
  - [Project Overview](#project-overview)
  - [Key Features](#key-features)
  - [Dataset](#dataset)
  - [Technologies Used](#technologies-used)
  - [Prerequisites](#prerequisites)
  - [Installation \& Usage](#installation--usage)
  - [Visualizations](#visualizations)
  - [Contact](#contact)

---

## Project Overview

This project provides an in-depth analysis and visualization of COVID-19 data, with a specific focus on understanding the primary causes of death and associated patient condition groups. Utilizing Python and various data science libraries, this Jupyter Notebook explores patterns and presents insights into the factors contributing to COVID-19 mortality. The goal is to offer a clear, data-driven perspective on the pandemic's impact through comprehensive analysis and compelling visual storytelling.

---

## Key Features

* **Data Cleaning and Preparation:** Processing and preparing the raw COVID-19 data from multiple sources for accurate analysis.
* **Exploratory Data Analysis (EDA):** Investigating the dataset to uncover global and regional patterns, anomalies, and insights regarding COVID-19 infection rates, mortality, testing efforts, and recovery trends.
* **Geographical Trend Analysis:** Visualizing the pandemic's spread, recovery patterns (e.g., "Recover World Map"), and testing distribution across continents and countries.
* **Comparative Regional Analysis:** Identifying and comparing key COVID-19 metrics, such as top infected countries/regions (e.g., "Top Infected") and testing rates by continent.
* **Mortality and Condition Analysis:** In-depth analysis of COVID-19 related deaths, including the identification of prevalent contributing conditions and condition groups, utilizing visualizations like word clouds (e.g., "Word Cloud Cause of Death") to highlight key factors.
* **Comprehensive Data Visualization:** Employing a variety of static and interactive visualization techniques to clearly present findings. This includes leveraging libraries like `matplotlib` for charts and graphs, `wordcloud` for textual data representation, and `plotly` for potentially interactive dashboards or figures.

---

## Dataset

The analysis in this notebook is based on a collection of three primary CSV files:

1.  **`covid.csv`**: This file likely contains general COVID-19 case data, such as confirmed cases, active cases, testing numbers, and other relevant metrics, potentially categorized by country or region over time.
2.  **`covid_grouped.csv`**: This file appears to present COVID-19 data that has been grouped or aggregated. This could mean data summarized by specific criteria like continent, country, or particular time periods, possibly including summary statistics or trends.
3.  **`coviddeath.csv`**: This file specifically focuses on COVID-19 related mortality data. It most likely contains details regarding deaths, such as dates, locations, and potentially information about pre-existing patient conditions or condition groups that contributed to mortality, which is crucial for the cause-of-death analysis in this project.

The combination of these three files allows for a comprehensive analysis of various aspects of the COVID-19 pandemic, from general case trends to specific details regarding mortality.

---

## Technologies Used

* **Python 3.x**
* **Jupyter Notebook**
* **Libraries:**
    * `pandas`: For data manipulation and analysis.
    * `numpy`: For numerical operations.
    * `matplotlib`: For static, animated, and interactive visualizations.
    * `plotly`: For interactive and publication-quality graphs (plotly.js setup was noted in the notebook).
    * `wordcloud`: For generating word cloud images.

---

## Prerequisites

Before running the notebook, ensure you have the following installed:
* Python 3.7 or higher.
* Jupyter Notebook or JupyterLab.
* The Python libraries listed under [Technologies Used](#technologies-used).

---

## Installation & Usage

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/your-repository-name.git](https://github.com/your-username/your-repository-name.git)
    cd your-repository-name
    ```
2.  **Create a virtual environment (recommended):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```
3.  **Install the required libraries:**
    It's good practice to include a `requirements.txt` file in your repository. You can create one using:
    ```bash
    pip freeze > requirements.txt
    ```
    Then, users can install dependencies using:
    ```bash
    pip install -r requirements.txt
    ```
    If you don't have a `requirements.txt`, list the manual pip install commands:
    ```bash
    pip install pandas numpy matplotlib plotly wordcloud
    ```
4.  **Launch Jupyter Notebook or JupyterLab:**
    ```bash
    jupyter notebook
    ```
    or
    ```bash
    jupyter lab
    ```
5.  **Open and run the `Covid 19.ipynb` notebook.**

---

## Visualizations

This project features several visualizations to illustrate the findings:

![Test by Continent](testbycontinent.png)

![Top Infected](topinfected.png)

![Recover World Map](recovermap.png)

![Word Cloud Cause of Death](wordcloudcod.png)

---

## Contact

**Umar Khairur Rahman**
* GitHub: `https://github.com/FBNajis` 
* Email: `umarkhairur@gmail.com` 
* LinkedIn: `https://www.linkedin.com/in/umar-khairur-rahman-168739258/`

Project Link: `https://github.com/FBNajis/Covid-19-Analysis-and-Visualization`

---
