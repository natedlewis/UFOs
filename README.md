# UFOs

## Background

### 0.2
In this project, we are working with Dana to create an interactive webpage that allows readers to track UFO sightings. The raw data provided by Dana is stored in a JavaScript array. Our intital task is to transfrom the data into a tidy table and create filters that will react to user input using D3. Lastly, we will place the table into an HTML file for optimal viewing and add customality using Bootstrap.

1) JS: Create a filterable table to display the data
2) The first step in transitioning the data from an array to a table is to create the appropriate variables using var, let, or const. Open VS Code and create a file in our repo folder named app.js. This is where we'll keep the code that builds the HTML table and fills it with data from data.js.
3) Create template
4) Once the template has been created, Dana can begin to code the JavaScript portion by first importing the data and then referencing it with a variable.

### 0.4
In this module, you'll You'll also create filters to make this table fully dynamic, meaning that it will react to user input, and then place the table into an HTML file for easy viewing.

You'll customize your webpage using Bootstrap, and equip your table with several fully functional filters that will allow users to interact with our visualizations. Watch the video to learn more about the specific data project you'll be working on.

### 2.2
Building a page that contains JavaScript will require Dana to link additional JavaScript files to the index.html file that she'll be working on later. This means keeping track of multiple things at once: an HTML file, JavaScript files, images (for customizing the webpage) and a CSS style sheet. Therefore, it's a good idea for Dana to establish a solid folder structure now instead of when she's elbow deep in creating her JavaScript functions.

### 2.4
Dana's goal is to create an interactive webpage that allows readers to parse the data around UFO sightings. So, she essentially needs to build two things: the webpage that will allow users to view the data (HTML) and a dynamic table that will present it (JavaScript).

Typically, developers build HTML and JavaScript elements somewhat simultaneously because they complement each other. For example, the JavaScript table will be referenced within the HTML code, and different HTML components will be referenced within the JavaScript code. Because these files are so closely linked, Dana will switch between building the JavaScript table (within the app.js file) and the HTML page (within an index.html file).

D3 is a JavaScript library that produces sophisticated and highly dynamic graphics in an HTML webpage. It is often used by data professionals to create dashboards, or a collection of visual data (such as graphs and maps), for presentation.

Although we aren't building the HTML right now—we'll do this after we put together the code—we already know that the data will fit into that tag because it's a standard table tag that is used often in HTML, with or without JavaScript enhancements.

### 4.1
The array containing UFO sightings is huge. Dana knows that iterating through it is inevitable, which means she will definitely need for loops. Feeling bolstered by her practice with arrow functions, Dana is ready to up the difficulty a bit by exploring how to create for loops in JavaScript.

### 5.1
We'll need to iterate through the array of objects in our data file and then append them to a table row.

### 5.2
Now Dana is ready to start adding data to her table. To do so, she'll need to create another function specifically for building the table. Data from the data.js file will be inserted into the table, row by row. This sounds like iterating through an array using a for loopforEach, doesn't it?

This time, we'll use a forEach function, which loops through the array in the same way as a for loop. The difference is that forEach works only with arrays. Another benefit is that forEach can be combined with an arrow function, once again making the code more concise and easy to read.

### 5.3
The code we helped create will add every object in ou data.js file to the table. Bundled into one tidy package, every sighting will be available for Dana (and her readers) to view! There are a lot of objects, though, which will make the table huge! There will be hundreds of rows of sightings in the table, which is entirely too much for one person to reasonably look through and study. Therefore, the next step is to add the ability to filter the data. We'll be using D3.js to help Dana with this part.

### Challenge
Dana’s webpage and dynamic table are working as intended, but she’d like to provide a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. In addition to the date, you’ll add table filters for the city, state, country, and shape.

## Overview of Project
Explain the purpose of this analysis.

## Results
Describe to Dana how someone might use the new webpage by walking her through the process of using the search criteria. Use images of your webpage during the filtering process to support your explanation.

## Summary
In a summary statement, describe one drawback of this new design and two recommendations for further development.