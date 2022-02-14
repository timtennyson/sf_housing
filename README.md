# San Francisco Housing Market Rental Opportunity Analyzer

This application analyzes the average rental income vs cost per square foot over time for various neighborhoods
in San Francisco

## Technologies
[Python3.7](https://www.python.org/)

[Jupyter Lab](https://jupyter.org/)

[Pandas](https://pandas.pydata.org)

[Pathlib](https://docs.python.org/3/library/pathlib.html) 

[hvplot](https://hvplot.holoviz.org/user_guide/Introduction.html)



## Installation guide
In order to run this application you'll need to install Python3.7 in conjunction with jupyter lab along with the libraries linked above. You'll also need to install the libraries listed above. 

## Part 1)-- 

### 1) Calculate and Plot Housing Units Per Year
Here we create a dataframe to show the number of housing units in San Francisco by year and plot it using the
hvplot function. The data is organized into a bar chart for each year.

### 2) Create a prices per square foot/ Rent Dataframe and Plot
Here a dataframe is created to show the prices per square foot and gross rent.
### 3)Plot price per square foot/Rent
We use hvplot to plot the these two datasets on a single line plot to compare the price per square foot with the average rental rates over time.

## Part 2)-- Compare Average Sale Prices By Neighborhood

### 1) Create a dataframe to group the original dataframe by neighborhood
A dataframe is created using the 'groupby' method to show the mean values for sale price per square foot vs rent, organized by year and then by neighborhood.

### 2) Plot the Data

We use hvplot to create an interactive line chart that shows the comparison between rental income and sale price over time with a dropdown to select the neighborhood.

## Part 3) Interactive Neighborhood Map

Here we use hvplot and Geoviews to create a map that plots the coordinates of the various neighborhoods. The color of each plot point represents the rental rate and the size of the plot represents the cost per square foot.


## Conclusions

While values are declining in a few neighborhoods, rental rates are not. I would recommend finding properties that are experiencing growth in both property value and rental rates as an optimal investment.

## Contributors

Tim Tennyson 
<ttennyson.xyz@gmail.com>

License: Open source, free distribution/reproduction
