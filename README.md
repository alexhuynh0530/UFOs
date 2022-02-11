# An Analysis of dynamic webpages with JavaSript, HTML and Bootstrap

## Overview of Project

### Purpose

This is an anlayis of creating dynamic webpages using web scraping methods to extract data using the following:
- JavaScript
- HTML, CSS and Bootstrap

Use case:
We build a table using data stored in a JavaScript array. We also create filters to make this table fully dynamic, meaning that it will react to user input, and then place the table into an HTML file for easy viewing.

We customize our webpage using Bootstrap, and equip our table with several fully functional filters that will allow users to interact with our visualizations. 

## Results

### UFO sitings dynamic webpage

Using JavaScript and HTML, we write code in your index.html file to create table filters for the city, state, country, and shape, as shown in the following image:

![filters.png](https://github.com/alexhuynh0530/UFOs/blob/main/static/images/filters.png)

Using JavaScript, we use a function that saves the element, value, and id of the filter that was changed. Then, create a another function to loop through the dataset and keep only the results that match the search criteria. The webpage will be updated with the search criteria after pressing "Enter".

#### Example filter using Date = "1/2/2010", State = "ca", and pressing "Enter"
![filter_example.png](https://github.com/alexhuynh0530/UFOs/blob/main/static/images/filter_example.png)




