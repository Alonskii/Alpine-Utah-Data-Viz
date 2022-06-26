# Alpine-Utah-Data-Viz

Visualization done by me with the data downloaded from the https://www.ncdc.noaa.gov/ 

This is a data visualization of the temperature high and low of Alpine between June 2017, and May 2022. 

The program 'data_headers.py' should be run first to generate the header rows of our data, so that we can get the accurate index position of our data, this should be done to avoid mistake. 

When you run the program, you'll discover that only one date had a missing data, because the error is handled appropriately, our code is able to generate a plot which skips over the missing data. 

I used the fill_between() method, which takes a series of x-values
and two series of y-values, and fills the space between the two y-value series to show the range between the high and low temperatures. 

The alpha argument, controls a color’s transparency. By setting alpha to 0.5, we make the red and blue plot lines appear lighter. 
