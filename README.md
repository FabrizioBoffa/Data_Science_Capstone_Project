## Coursera Capstone Project - The Battle of Neighborhoods
### Analysis of London residential housing market
### *January 2021 - Fabrizio Boffa*

Main notebook file is "CapstoneProject.ipynb".

Before running the notebook please check and install eventual missing libraries in your python kernel.
Here are the libraries used:

*import os
from dateutil.relativedelta import relativedelta
import pandas as pd
import numpy as np
from sklearn.preprocessing import MinMaxScaler
from sklearn.pipeline import make_pipeline
from sklearn.preprocessing import PolynomialFeatures
from sklearn.linear_model import LinearRegression
from sklearn.cluster import KMeans
from sklearn.cluster import DBSCAN
from sklearn.metrics import silhouette_score
import json
import requests
import matplotlib.pyplot as plt
import matplotlib.ticker as mtick
from matplotlib import rcParams
import seaborn as sns
import folium
from shapely.geometry import shape, Point
from bokeh.io import show, output_notebook, curdoc
from bokeh.plotting import figure 
from bokeh.layouts import column as b_column
from bokeh.layouts import row as b_row
from bokeh.models import CustomJS, Legend, LegendItem, ColumnDataSource, Select, Label , Div, Title
from bokeh.themes import Theme
from geopy import distance*

Also, a valid Foursquare Client ID and Secret must be provided in "# FOURSQUARE API DATA ACQUISITION" cell, with a sufficent daily calls quota (about 2.000 or above).

Complete HTML output of this notebook is available at:
https://fabrizioboffa.github.io/CapstoneProject.html

"Web scraping algorithm.ipynb" has been used to create json data files in /json/houses/ directory.
