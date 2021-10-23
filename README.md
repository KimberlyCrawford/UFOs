# UFOs

# Overview
Creating dynamic content with JavaScript to produce an in-depth analysis of UFO sightings around the world.

## Purpose

The purpose of this project was to create an interactive webpage using HTML and a dynamic table with JavaScript that allows readers to parse data around UFO sightings and see the results on their screen. 

NOTE: HTML and JavaScript elements were created simultaneously because they complemented each other. For example, the JavaScript table was referenced within the HTML code, and different HTML components were referenced within the JavaScript code. Because these files were so closely linked, the developer switched between building the JavaScript table (within the app.js file) and the HTML page (within an index.html file). 

## Data

The data for this project was stored in a JavaScript array and consisted of single events (UFO sightings) as shown in the example below:

![Data_array_event.png](https://github.com/KimberlyCrawford/UFOs/blob/main/static/images/Data_array_event.png)

## Steps in Project

1) Created the index.html file (the WebPage) to display the information shown in the following storyboard:

![Storyboard.png](https://github.com/KimberlyCrawford/UFOs/blob/main/static/images/Storyboard.png)

2) Created the style.css sheet to customize the WebPage.

3) Created an Images folder to hold all images displayed on the WebPage.

4) Created the app.js file to build the JavaScript code to align with the WebPage. 

- Imported data from data.js file.
- Pointed the data to the HTML page using D3 which is a JavaScript library that produces sophisticated and highly dynamic graphics in an HTML webpage. The code declared a variable, tbody, and used d3.select to tell JavaScript to look for the <tbody> tags in the HTML.
- Used JavaScript functions to build the table. Used the forEach function to iterate through each variable in the data. 
- Created a second function using the the popular library, D3.js, to equip the website to "listen" for events, such as a user clicking a button and filter by date. When the button is clicked, D3 detected the click and reacted accordingly.

The following was the WebPage result:

![Table_filtered_by_date.png](https://github.com/KimberlyCrawford/UFOs/blob/main/static/images//Table_filtered_by_date.png)


## Challenge

The purpose of this challenge was to expand on the project completed during the module and use Javascript, HTML, and CSS to create a custom webpage that showcased different UFO sitings around the world and allowing users to filter for multiple criteria at the same time. The challenge consisted of one technical analysis deliverable and a written report as follows.

### Deliverable 1 - Filtered UFO Sightings on Multiple Criteria

Using JavaScript and HTML, the code was modified in the index.html file to create additional table filters for the city, state, country, and shape as shown below:

The handleClick() function was replaced in the app.js file with a new function that saved the element, value, and id of the filter that was changed above. A new function was created to loop through the dataset and keep only the results that match the search criteria. The webpage was updated with the search criteria.

### Deliverable 2 - Written Analysis

The following written analysis contains the results and summary of the project:

## Results: 

The process of using the search criteria to filter the data on the Webpage includes the following:

1) 

2)

3)

## Summary: 

Although the Webpage design met the project requirements, one drawback of the new design was?

Two recommendations for further development include:

1)

2)
