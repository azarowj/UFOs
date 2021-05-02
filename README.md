# UFOs

## Overview

- The purpose of this project is to create a webpage where we can filter through a specific dataset of UFO sightings. We have added multiple filters to the table of data. These filters include the date, city, state, country, and shape.

## Summary

- To perform a search, you click in the field for the criteria you are interested in. There is an example in each filter box so that you know how you are expected to enter the criteria yourself. Once you type in the filtered criteria, you click enter. The filtered dataset can then be seen on the right. An example of this can be seen in the below image.
- (https://github.com/azarowj/UFOs/blob/main/static/images/FilterSearch.png)

## Results

- The webpage does not provide references to where it got the data from. This data could be completely made up for all we know. Also, we do not know the range of date in the data set. When attempting to filter by date, we could be inputting a date that either has no data, or is not even in the range of the dataset.
- I would recommend putting in elements to handle errors. Specifically when a filter returns no value, and why. Is it because the date it outside of our date range or is it because that particular date is inside our date range but holds no data?
- I would also suggest doing an ETL process on the dataset. For the shape attribute, are we considereing a sphere and a circle to be the same thing? If so, that should be adjusted in the dataset before it is loaded to the webpage.
