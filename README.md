
![Logo](https://logos-download.com/wp-content/uploads/2016/04/Rossmann_logo_logotype.png)


# Rossmann Store Chain Sales Prediction

Rossmann store chain is one of largest
drugstore chain of Europe with at
present more than 56000 employees
and over 4000 stores. Daily sales at
these stores can be influenced by many
factors like is today a state or a school
holiday or if the store is running some
kind of promo today and also by
seasonality and locality of the stores. In this project by looking
at the features present in the datasets and by analyzing their relation
and the effect they have on the target variables sales we have built one
robust ML model that can predict the daily sales at these stores for up to 
six weeks in advance
## Install

This project requires Python and the following Python libraries installed

* [NumPy](https://numpy.org/)
* [Pandas](https://pandas.pydata.org/)
* [Matplotlib](https://matplotlib.org/)
* [Seaborn](https://seaborn.pydata.org/)
* [scikit-learn](https://scikit-learn.org/stable/)

We also need to have software installed to run and execute a Jupyter Notebook.

We can install the [Anaconda](https://www.anaconda.com/) distribution of python
which already has most of the above packages and more included or we can also run the 
whole notebook on google colab without going through the process of installing all the
libraries locally in our machine.


## Code

The main code is provided in the `Rossmann_Sales_Prediction_Capstone_Project.ipynb`
notebook file. We will also require the two datasets
`Rossmann Stores Data.zip` which needs to be unzipped 
to get the actual csv file and `store.csv` to run the
notebook. 
## Run

In a terminal or command window, navigate to the top-level project directory (that contains this README) 
and run one of the following commands:

```
ipython notebook Rossmann_Sales_Prediction_Capstone_Project.ipnyb
```
or
```
jupyter notebook Rossmann_Sales_Prediction_Capstone_Project.ipnyb
```
or open with Jupyter Lab
```
jupyter lab
```
This will open the Jupyter Notebook software and project
file in our browser
## Data

We have two datasets `Rossmann Stores Data.csv` and 
`store.csv` . The Rossmann Stores dataset consists of
around 1017209 datapoints with each datapoint having 
9 features.

### Features

    1.  Store : A unique id for each store
    2.  DayOfWeek : Day of week from the date of the data point
    3.  Date : Date of the observation
    4.  Sales : The turnover for any given day
    5.  Customers : The number of customers on a given day
    6.  Open : An indicator for whether the store was open: 0 = closed, 1 = open
    7.  Promo : Indicates whether a store is running a promo on that day 
    8.  StateHoliday : Indicates a State Holiday on a given day
    9.  SchoolHoliday : Indicates a school holiday on a given day

The store dataset is holding 1115 observations each having 10 features or variables.

### Features

    1. Store : A unique id for each store
    2. StoreType : Differentiates between 4 different store models: a, b, c, d
    3. Assortment : Describes an assortment level: a = basic, b = extra, c = extended
    4. CompetitionDistance : Distance in meters to the nearest competitor store
    5. CompetitionOpenSinceMonth : Gives the approximate month of the time the nearest competitor was opened
    6. CompetitionOpenSinceYear : Gives the approximate year of the time the nearest competitor was opened
    7. Promo2 : Promo2 is a continuing and consecutive promotion for some stores: 0 = store is not participating, 1 = store is participating
    8. Promo2SinceWeek[Week/Year] : Describes the year and calendar week when the store started participating in Promo2
    9. PromoInterval - describes the consecutive intervals Promo2 is started, naming the months the promotion is started anew.

### Target Variable : `Sales`


## 🛠 Algorithms Used
Ridge Regression , Decision Tree , Gradient Boost and Random Forest


## Authors

- [@Yash1289](https://github.com/Yash1289)


## 🚀 About Me
I'm an aspriring data scientist who loves to `deeply` work with data


## 🔗 Links
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shaurabh-pandey-69484921a/)


