# titanic_survival

## Overview

This python project aims to predict survival outcomes from the 1912 Titanic disaster based on each passenger’s features (pclass, name, sex, age, sibsp, parch, ticket, fare, cabin, embarked).

The main code [`titanic_survival.ipynb`](https://github.com/adsasmita/titanic_survival/blob/master/titanic_survival.ipynb) is presented in a [Jupyter Notebook](https://github.com/jupyter/notebook) / iPython notebook for readability purposes.

Visualization codes are contained in [`visuals.py`](https://github.com/adsasmita/titanic_survival_exploration/blob/master/visuals.py)

## Data

The dataset used in this project is included as `titanic_data.csv`. This dataset is provided by Udacity and contains the following attributes:

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
