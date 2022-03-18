# UFOs

## Overview of Project
In this project, we are working with Dana to create an interactive webpage that allows readers to track UFO sightings. To fulfill Dana's request, we must build the webpage that will allow users to view the data along with a dynamic table that will present it. This involves working with HTML and JavaScript elements. A JavaScript table can be referenced within HTML code, and different HTML components may be referenced within the JavaScript code. Dana provided us with data stored in a JavaScript array. The initial step involves transforming the data from an array to a table. We can do this within JavaScript by creating functions to build the HTML table, and fill it in with appropriate data. Lastly, we will customize the webpage using Bootstrap, and integrate several filters that will allow users to interact with the table.

#### Storyboard
![storyboard](https://github.com/natedlewis/UFOs/blob/main/results/storyboard.png?raw=true)


#### Single value within array
```java
var data = [
  {
    datetime: "1/1/2010",
    city: "benton",
    state: "ar",
    country: "us",
    shape: "circle",
    durationMinutes: "5 mins.",
    comments: "4 bright green circles high in the sky going in circles then one bright green light at my front door."
  }
```

## Results
Describe to Dana how someone might use the new webpage by walking her through the process of using the search criteria. Use images of your webpage during the filtering process to support your explanation.


![title](https://github.com/natedlewis/UFOs/blob/main/title.png?raw=true)
![table_unfiltered](https://github.com/natedlewis/UFOs/blob/main/img_1.png?raw=true)
![table_filtered](https://github.com/natedlewis/UFOs/blob/main/img_2.png?raw=true)

Dana’s webpage and dynamic table are working as intended, but she’d like to provide a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. In addition to the date, you’ll add table filters for the city, state, country, and shape.

## Summary
In a summary statement, describe one drawback of this new design and two recommendations for further development.

