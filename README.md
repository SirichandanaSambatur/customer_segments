# Identifying Customer Segments
In this project unsupervised learning techniques are applied on product spending data collected for customers of a wholesale distributor in Lisbon, Portugal to identify customer segments hidden in the data.
Firstly, the data is explored by selecting a small subset to sample and determine if any product categories highly correlate with one another. Afterwards, the data is preprocessed by scaling each product category and then identifying (and removing) unwanted outliers.
With the good, clean customer spending data, PCA transformations are applied to the data and implement clustering algorithms to segment the transformed customer data. Finally, compare the segmentation found with an additional labeling and consider ways this information could assist the wholesale distributor with future service changes.

This project contains three files:

- `customer_segments.ipynb`: This is the main file where work on the project has been performed. 
- `customers.csv`: The project dataset. This data must be loaded in the notebook.
- `visuals.py`: This Python script provides supplementary visualizations for the project.

## Software and Libraries
This project uses the following software and Python libraries:

- [Python 2.7](https://www.python.org/download/releases/2.7/)
- [NumPy](http://www.numpy.org/)
- [pandas](http://pandas.pydata.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [matplotlib](http://matplotlib.org/)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html).

## Running the project

The project is built in an iPython notebook and a notebook application such as 'iPython' or 'Jupyter Notebook' is required for running the project. To run the project, open the '.ipynb' file with a notebook application and run all the cells. The analysis of the dataset can also be seen in the '.html' file without actually running the project.

