# Airbnb_Seattle_Data_Analysis

### Table of Contents

1. [Installation](#installation)
2. [Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

This project uses Python 3, besides Jupyter Notebook. The list of libraries to run this project are:
* Pandas
* Numpy
* MatplotLib
* Seaborn
* XGBoost


## Motivation<a name="motivation"></a>

In this project, I want to investigate the AirBnB dataset from Seattle to answer the following questions:
1. What distinguishes hosts that have Superhost status? Do all Superhosts properly qualify the criteria that AirBnB has set for them?
2. What time of the year are AirBnBs most popular in Seattle? Are specific holiday seasons more popular?
3. What are the most important characteristics of a listing, and how do they influence price?

## File Descriptions <a name="files"></a>

The main code for this project is included in the notebook `Data Exploration with AirBnB.ipynb`. The notebook walks through all the steps of the CRISP-DM Process for analyzing the dataset to answer the above three questions. The code and results are also posted on Medium as a [blog post](https://medium.com/@ravishchawla/how-can-you-get-the-most-out-of-your-airbnb-listing-7df1fe4b0309).

Data for the project is not included because of large file sizes. To properly run the notebook, it must be placed in `data` -> `Seattle`. The directory should have the following files:
* `calendar.csv`
* `listings.csv`
* `reviews.csv`

Along with the AirBnB data, the Federal Holidays dataset (from [kaggle](https://www.kaggle.com/gsnehaa21/federal-holidays-usa-19662020)) will also have to be included in the `data` directory. This file is `usaholidays.csv`.

Charts used for the Medium blog post and the Notebook are included in the `charts` directory.

## Results<a name="results"></a>

The main findings of the code can be found at the post available [here](https://medium.com/@ravishchawla/how-can-you-get-the-most-out-of-your-airbnb-listing-7df1fe4b0309).


## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Credit to AirBnB for providing the data. You can find the Licensing for the data and other descriptive information at the Kaggle link available [here](https://www.kaggle.com/airbnb/seattle), and [here](https://www.kaggle.com/gsnehaa21/federal-holidays-usa-19662020/home). This code is free to use.
