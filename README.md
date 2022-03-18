# UFOs

## Overview of Project
In this project, we are working with Dana to create an interactive webpage that allows readers to track UFO sightings. To fulfill Dana's request, we must build the webpage that will allow users to view the data along with a dynamic table that will present it. This involves working with HTML and JavaScript elements. A JavaScript table can be referenced within HTML code, and different HTML components may be referenced within the JavaScript code. Dana provided us with data stored in a JavaScript array. The initial step involves transforming the data from an array to a table. We can do this within JavaScript by creating functions to build the HTML table, and fill it in with appropriate data. Lastly, we will customize the webpage using Bootstrap, and integrate several filters that will allow users to interact with the table.

#### Storyboard
![storyboard](https://github.com/natedlewis/UFOs/blob/main/results/storyboard.png?raw=true)


#### Single value within JavaScript array
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

#### Navigation bar, page header, and article
![title](https://github.com/natedlewis/UFOs/blob/main/results/title.png?raw=true)

#### Preset/unfiltered table

![table_unfiltered](https://github.com/natedlewis/UFOs/blob/main/results/table_unfiltered.png?raw=true)

#### Table reacting to user input and adjusting to project only UFO sightings within La Mesa

![tabe_filtered](https://github.com/natedlewis/UFOs/blob/main/results/tabe_filtered.png?raw=true)
> Filters may trigger indivually upon pressing enter, or just clicking off the input box. To remove a filter, simply delete any text within an input box, and press enter. They are case-sensitve. 


## Summary
One drawback to this new deisgn is that we're forced to manually input text into the input boxes. This desigen is inconvinent, and may lead to many spelling errors, or issues with inputting the proper date format. This problem would be an easy fix with futher customization. Integtating drop-down lists would ensure better usability for readers. Reworking the date filter box could trigger a drop down calender where users have the option to input a range of dates, or a single value.



