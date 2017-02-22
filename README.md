# titanic_survival

A machine learning project using [NumPy](http://www.numpy.org/) matrix library to predict passenger survival outcomes from the [1912 Titanic disaster](http://www.history.com/this-day-in-history/titanic-sinks).

## Overview

In 1912, the ship [RMS Titanic](https://en.wikipedia.org/wiki/RMS_Titanic) struck an iceberg on its maiden voyage and sank, resulting in the deaths of most of its passengers and crew. This project explores a subset of the RMS Titanic passenger manifest to determine which features best predict whether someone survived or did not survive.

This project aims to create decision functions that attempt to predict survival outcomes from the 1912 Titanic disaster based on each passenger’s features, such as sex and age. It starts with a simple algorithm, then increases its complexity until we are able to accurately predict the outcomes with at least 80% accuracy.

## Files

To open the main code, simply open [`titanic_survival.ipynb`](https://github.com/adsasmita/titanic_survival/blob/master/titanic_survival.ipynb) on any desktop browser, or you can download and run the cells in a Python 2 environment. The code is presented in a [Jupyter Notebook](https://github.com/jupyter/notebook) / iPython notebook for readability purposes.

Visualization codes are contained in [`visuals.py`](https://github.com/adsasmita/titanic_survival_exploration/blob/master/visuals.py)

## Data

The dataset used in this project is included as `titanic_data.csv`. This dataset contains the following attributes:

**Features**
- `pclass` : Passenger Class (1 = 1st; 2 = 2nd; 3 = 3rd)
- `name` : Name
- `sex` : Sex
- `age` : Age
- `sibsp` : Number of Siblings/Spouses Aboard
- `parch` : Number of Parents/Children Aboard
- `ticket` : Ticket Number
- `fare` : Passenger Fare
- `cabin` : Cabin
- `embarked` : Port of Embarkation (C = Cherbourg; Q = Queenstown; S = Southampton)

**Target Variable**
- `survival` : Survival (0 = No; 1 = Yes)

## Dependencies

This project requires **Python 2.7** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
