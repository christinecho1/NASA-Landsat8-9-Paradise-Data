# NASA SEES Algorithm
Reading real data files with temperature data - the problem was the temperature data was in 16-bit unsigned integers. And for our purposes it needs to be in Fahrenheight! 

Requirements:

1.  To read in the temperature values without destroying the position of each data value.
2.  Convert the temperature data from 16-bit unsigned integer into degrees Kelvin. From Kelvin, convert to degrees Celsius, then to Fahrenheit.
3.  There are conversion formulas for converting Kelvin into  our target temperature scales. Find the formula and convert them into code.
4.  Calculate minimum, maximum, median and mean land surface temperatures for each date.
5.  Output at least one converted text dataset.

#About The Data
More info about the data you will work with. These datasets map land surface temperatures before and during the California Paradise Fire in late 2018 and 2019. There are 4 datasets in text file format. Each cover the same geographic area on a different date. One of the datasets was captured as the fire was burning.
