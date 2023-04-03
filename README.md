# Project Overview

I will use web scraping to obtain NBA box scores, which I'll clean with BeautifulSoup. I'll then parse the data into pandas DataFrames for machine learning. By performing feature selection, I'll identify strong predictors, and train a machine learning model to make predictions. Lastly, I'll calculate rolling predictors and improve the model.

This is a complete end-to-end project, and where I will use web scraping, data cleaning, and machine learning.

**Project Steps**

* Scrape standings and box score data
* Clean up html with BeautifulSoup
* Parse the box scores to get a DataFrame
* Run feature selection to identify predictors
* Train an ML model
* Compute rolling predictors to improve the model

## Code

File overview:

* `get_data.ipynb` - download the box scores from basketball reference.
* `parse_data.ipynb` - clean the data to get a pandas DataFrame.
* `predict.ipynb` - make predictions using machine learning

# Local Setup

## Installation

* JupyerLab
* Python 3.8+
* Python packages
    * pandas
    * scikit-learn
    * beautifulsoup4
    * playwright

## Data

Dataset is scraped from Basketball Reference : https://www.basketball-reference.com/leagues/
