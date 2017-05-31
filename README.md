# Titanic Survival Exploration
The main objective of this project is to explore the 1912 Titanic data and to create decision functions that attempt to predict survival outcomes based on each passenger’s features, such as sex and age.

### Back ground

The sinking of RMS Titanic is one of the tragic marine disaster in the history. In the early morning of April 15, 1912, the titanic sunk after colliding with an iceberg during her maiden voyage. This shipwreck killed more than 1,500 out of the estimated 2,224 passengers and crew aboard.

One of the reasons that the Titanic shipwreck led to such a loss was that there were not enough lifeboats for the passengers and crew. However, some groups of people (such as women, children, the upper-class etc...) were more likely to survive than the others.

## Software Requirements

### Install

This project requires **Python 2.7** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html)

Udacity recommends our students install [Anaconda](https://www.continuum.io/downloads), a pre-packaged Python distribution that contains all of the necessary libraries and software for this project.

### Code

Template code is provided in the notebook `titanic_survival_exploration.ipynb` notebook file. Additional supporting code can be found in `titanic_visualizations.py`. While some code has already been implemented to get you started, you will need to implement additional functionality when requested to successfully complete the project.

### Run

In a terminal or command window, navigate to the top-level project directory `titanic_survival_exploration/` (that contains this README) and run **one** of the following commands:

```bash
jupyter notebook titanic_survival_exploration.ipynb
```
or
```bash
ipython notebook titanic_survival_exploration.ipynb
```

This will open the iPython Notebook software and project file in your web browser.

## Data

The dataset used in this project is included as `titanic_data.csv`. This dataset is provided by Udacity and contains the following attributes:

- `survival` : Survival (0 = No; 1 = Yes)
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

This project is a part of the Machine Learning Engineer Nanodegree program at [Udacity](https://www.udacity.com/).
