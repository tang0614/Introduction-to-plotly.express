# Introduction-to-plotly.express
covers line chart, scatter plot, box plot, histogram, bar chart and 3D plot
## INTRODUCTION
* In this kernel, we will learn how to use plotly.express and to compare it with plotly.graph_objs library. We can see that most graph can be done with express library with much simipler code.

    1. Plotly library: plotly.py is an interactive, open-source, and JavaScript-based graphing library for Python. Built on top of plotly.js, plotly.py is a high-level, declarative charting library that includes over 30 chart types, including scientific charts, 3D graphs, statistical charts, SVG maps, financial charts, and more.The ultimate responsibility of plotly.py is to produce Python dictionaries that can be serialized into a JSON data structure that represents a valid figure
    
    2. What is plotly.express and plotly.graph_objs?
        1. plotly.graph_objs provides a hierarchy of classes called "graph objects" that may be used to construct figures.
        2. Plotly Express is a terse, consistent, high-level wrapper around plotly.graph_objects for rapid data exploration and figure generation. Most plots are made with just one function call that accepts a **tidy Pandas data frame**, and a simple description of the plot you want to make.
        
## Content:
1. [Loading Data and Explanation of Features](#1)
1. [Line Charts](#2)
    1. Use plotly.graph_objs
        1. Draw single line
        2. Style line
        3. Draw multiple lines
    2. Use plotly.express
        1. Draw single line
        2. Style line
        3. Draw multiple lines
1. [Scatter Charts](#3)
    1. Use plotly.graph_objs draw scatter and line plot
    2. Use plotly.express 
        1. Scatter plot with color
        2. Scatter plot with facet
        3. Scatter Plot with categorical size and hover
        4. Scatter plot matrix
1. [Bar Charts](#4)
1. [Histogram](#5)
1. [Box Plot](#6)
1. [Heatmap](#7)
1. [3D Plot](#8)


## [See plots in html](https://nbviewer.jupyter.org/github/tang0614/Introduction-to-plotly.express/blob/master/express.ipynb)

