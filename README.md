## Coursera Capstone Project - The Battle of Neighborhoods
### Analysis of London residential housing market
### *January 2021 - Fabrizio Boffa*

Main notebook file is "CapstoneProject.ipynb".

Before running the notebook please check and install eventual missing libraries in your python kernel.
Here are the libraries used:

*import os<br>
from dateutil.relativedelta import relativedelta<br>
import pandas as pd<br>
import numpy as np<br>
from sklearn.preprocessing import MinMaxScaler<br>
from sklearn.pipeline import make_pipeline<br>
from sklearn.preprocessing import PolynomialFeatures<br>
from sklearn.linear_model import LinearRegression<br>
from sklearn.cluster import KMeans<br>
from sklearn.cluster import DBSCAN<br>
from sklearn.metrics import silhouette_score<br>
import json<br>
import requests<br>
import matplotlib.pyplot as plt<br>
import matplotlib.ticker as mtick<br>
from matplotlib import rcParams<br>
import seaborn as sns<br>
import folium<br>
from shapely.geometry import shape, Point<br>
from bokeh.io import show, output_notebook, curdoc<br>
from bokeh.plotting import figure <br>
from bokeh.layouts import column as b_column<br>
from bokeh.layouts import row as b_row<br>
from bokeh.models import CustomJS, Legend, LegendItem, ColumnDataSource, Select, Label , Div, Title<br>
from bokeh.themes import Theme<br>
from geopy import distance*<br>

Also, a valid Foursquare Client ID and Secret must be provided in "# FOURSQUARE API DATA ACQUISITION" cell, with a sufficent daily calls quota (about 2.000 or above).

Complete HTML output of this notebook is available at:
https://fabrizioboffa.github.io/CapstoneProject.html

"Web scraping algorithm.ipynb" has been used to create json data files in /json/houses/ directory.
