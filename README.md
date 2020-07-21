# Covid-19 Analysis

### Install

This project requires **Python 3.x** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [xgboost](https://pypi.org/project/xgboost/)

You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html)

I recommend installing [Anaconda](https://www.continuum.io/downloads), a pre-packaged Python distribution that contains all of the necessary libraries and software for this project.

To view the Tableau dashboards, you will need to install either [Tableau Desktop](https://www.tableau.com/products/desktop/download) or [Tableau Reader](https://www.tableau.com/products/reader)
### Motivation

In this project, I wanted to see if I can predict which US counties will have 0.1%, 0.2%, and 1% of their population be infected with Covid-19. My hope is to use the results of mt analysis to also see if I could get similar results with other viruses or future pandemics.

### Files

The files in the repository include:
- Covid-19.ipnyb: Jupyter notebook used for the analysis.
- covidBook.twbx: Tableau notebook used to create visualizations.
- covid.csv: Training dataset.
- covid4.csv: dataset with predicted values.

### Summary
In the analysis I was able to predict counties with 0.1%, 0.2%, and 1% infected population with f1 scores of 0.95, 0.94, and 0.99 repectively. I Then decided to try the analysis again but now without considering the size of 
the counties. My new f1 scores are 0.94, 0.94, 0.99. Due to the availability of my data, I only had data for 2,713 counties out of 3,141.
