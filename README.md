# UFOs by Alec Ngai

## Overview of Project:
We want the user to be able to filter the data using multiple filters and respond in realtime. Create, populate, and dynamically filter a table using JavaScript and HTML. Linking the two together, we will further our understanding of how to create dashboards using Javascript, HTML and CSS. The request from a client was to display a table organizing UFO data stored as a JavaScript array. The client wanted the ability to filter by multiple criteria creating a dynamic website.  The table was created using JavaScript, while HTML/CSS and Bootstrap were used to modify the aesthetics of the website. 

## Results:
### Welcome to UFO Sightings! 

This is the intial apperance of the filters, there are 5 different filters which correspond to the different columns in the data. 

Date, City, State, Country, Shape each can be mixed and matched to further your search in a more detailed matter.

![Pic 2](https://github.com/Baylex/UFOs/blob/main/static/images/bottom.PNG)

### How the filters appear after being used: 
By typing in the suggested placeholder elements as the filters, the result returns 2 matches.  These filter boxes are not case sensative and will respond after the users clicks out of the box, this will signify a change and trigger the App.js to update the tables.  

![Pic 3](https://github.com/Baylex/UFOs/blob/main/static/images/working_filters.PNG)


## Summary: 

### Drawback:
There is no sort function, or range function. Therefore you cannot search for a range of dates, or select a range of shapes. This creates a bad user experience, unless you are looking for a very specific type of encounter. In addition, some of the infomaiton an data in Duration is inconsistent formating, for example "About 14 minutes or 10:00, or 4-6 minutes". This renders the Duraction column useless unless we reformate the data, and include a range function since it does not make sense to search for an event in a specifc minute period. 

### Recommendations: 
1. Add a sort function for each of the columns, ascending or descending, to help the user have a better browsing experience. 
2. Add multiple ranges for multiple functions this will allow the user to specify exactly in which time period or which shapes he/she wants. 
3. Reformat the Duraction column and add a range sort filter, to allow the user to find out a period of time. 
4. Add a key word filter, which will sort the comments if the word exists within, this might help the user in someway if there are looking for a specific experience for example. "Forest", "Sky" 
