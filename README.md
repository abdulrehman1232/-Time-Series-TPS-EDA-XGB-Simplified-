# Book Sales Forecasting
This project is part of the Kaggle competition where participants are tasked to forecast book sales for multiple stores across different countries during the year 2021. The dataset provided consists of historical sales data for a specific book sold in each store from January 2013 to December 2020. The goal is to predict the number of copies sold for each book in each store for the entire year 2021.

## Dataset Description
The dataset provided contains one CSV file named sales_data.csv, which contains the following columns:

date: the date of the sale, formatted as YYYY-MM-DD </br>
country: the name of the country where the store is located </br>
store: the name or ID of the store </br>
product: the name or ID of the book sold </br>
num_sold: the number of copies sold on that date for that book in that store </br>
## Project Structure
The project is structured as follows:

data: contains the raw data file provided by the competition organizers </br>
notebooks: contains Jupyter notebooks for data exploration, preprocessing, modeling, and evaluation </br>
models: contains trained models serialized using pickle </br>
submissions: contains the CSV files submitted to the competition leaderboard </br>
## Requirements
To run the Jupyter notebooks in this project, you need to have the following Python packages installed:

pandas </br>
numpy </br>
matplotlib </br>
seaborn </br>
scikit-learn </br>
xgboost </br>
You can install them using pip or conda.

## Usage
To reproduce the results in this project, follow these steps:

## Clone this repository to your local machine.
Download the competition dataset from Kaggle and extract it into the data directory. </br>
Open Jupyter Notebook or JupyterLab and navigate to the notebooks directory. </br>
Run the notebooks: </br>
01_data_exploration.ipynb: explore the dataset and visualize its characteristics. </br>
## Credits
This project was created by Abdul Rehman. The dataset was provided by Kaggle as part of the Book Sales Forecasting competition. Some code snippets and ideas were borrowed from the Kaggle community and other online sources, which are cited in the notebooks.
