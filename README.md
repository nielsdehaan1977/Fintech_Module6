# Fintech_Module6
---

![6-4-geoviews-plot.png](https://github.com/nielsdehaan1977/Fintech_Module6/blob/main/Images/6-4-geoviews-plot.png)

## Housing Rental Analysis, interactive visualizations and geospatial analysis

## san_francisco_housing.ipynb
---

### This Jupyter notebook can be used as a Housing Rental Analysis tool and utilizes interactive visualizations and geospatial analysis to provide the user with information to find viable investment opportunities in real estate. 

The tool first analyzes the overall trend in an area/city and then goes deeper into sections of that area/city by comparing trends in neighborhoods. That are visible in various interactive visualizations to help the user decide where best to invest. 
The tool uses the PyViz ecosystem which includes boht hvPlot and GeoViews. PyViz is a Python visualization package that provides a single platform for accessing multiple visualization libraries.

---
## Table of Content

- [Tech](#technologies)
- [Installation Guide](#installation-guide)
- [Usage](#usage)
- [Contributor(s)](#contributor(s))
- [License(s)](#license(s))

---
## Tech

This project leverages python 3.9 and Jupyter Lab with the following packages:

* `Python 3.9`
* `Jupyter lab`

* [JupyterLab](https://jupyter.org/) - Jupyter Lab is the latest web-based interactive development environment for notebooks, code, and data.

* [pandas](https://pandas.pydata.org/pandas-docs/stable/index.html) - Pandas is an open source, BSD-licensed library providing high-performance, easy-to-use data structures and data analysis tools for the Python programming language.

* [hvplot](https://hvplot.holoviz.org/user_guide/Plotting.html) - hvplot is generate plots from Pandas DataFrames and many other data structures of the PyData ecosystem.

* [geoviews](https://geoviews.org/) - GeoViews is a Python library that makes it easy to explore and visualize geographical, meteorological, and oceanographic datasets
---

## Installation Guide

### Before running the application first install the following dependencies in either Gitbash or Terminal. (If not already installed)

#### Step1: Activate dev environment in Gitbash or Terminal to do so type:
```python
    conda activate dev
```
#### Step2: install the following libraries (if not installed yet) by typing:
```python
    pip install pandas
    conda install -c pyviz hvplot geoviews
    
```
#### Step3: Start Jupyter Lab
Jupyter Lab can be started by:
1. Activate your developer environment in Terminal or Git Bash (already done in step 1)
2. Type "jupyter lab --ContentsManager.allow_hidden=True" press enter (This will open Jupyter Lab in a mode where you can also see hidden files)

![JupyterLab](https://github.com/nielsdehaan1977/Fintech_Module6/blob/main/Images/JupyterLab.PNG)


## Usage

To use the San Francisco housing jupyter lab notebook, simply clone the full repository and open the **san_francisco_housing.ipynb** file in Jupyter Lab. 

The tool will go through all the steps of financial planning:

### Analyse city/area data
* Evaluate the sqft price for renting and buying in a city/area. 

### Analyse individual neighborhoods in city/area
* Evaluate the sqft price for renting and buying per neighborhood in a city/area. 

### Visualize results for easy decision making
* Tool provides a number of useful interactive graphs and an interactive map to make it easier to understand where viable investment opportunities in an area exist. 

## Contributor(s)

This project was created by Niels de Haan (nlsdhn@gmail.com)

---

## License(s)

MIT
