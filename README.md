# Module-11-Challenge   UFO Analysis
## Overview of Project ##
The purpose of this Project is to enhance the existing UFO sightings webpage in order to accomodate filtering based on city, state, country and shape. This would allows filtering based on multiple criteria at the same time. 

The analysis consisted of the following:
- Filter UFO sightings on multiple criteria

### Resources ###
- Data Source: UFO Dataset
- Libraries/Dependencies: BootStrap 4.0.0, D3.js
- Software: HTML/CSS, JavaScript, Visual Studio Code

## Results ##
### Updated Search Filters ###
The UFO sightings webpage has been updated now to accomodate multiple search criteria, such as city, state, country, and shape.<br>
The following figure depicts the initial webpage <br>
![initial](/static/images/11-ufo0.png) <br><br>

In order to conduct a search, a user just needs to enter any value in the input fields, and the filtering takes place automatically. 
The Search can be conducted on different asspects. An example of a filtered search is given below, where city, state, country and shpae were used.<br>
![full](/static/images/11-ufo1.png) <br><br>

The user can also filter on just one criteria, as shown below <br>
![full](/static/images/11-ufo1.png) <br><br>

## Summary ##
### Drawbacks of Current Design ###
- The input is not checked for errors. That is, if the user enters USC instead of US, no data is displayed. 
- The user needs to go through the dataset to understand the values for each of the search parameters. That is, the user will need to go through the datat to know that that country codes are two digits (i.e. CA, US, etc). 

### Recomendations for Improvements ###
- A dropdown list would limit the input to the filters, hence reducing errors
- A range for the date can also be provided. So that users can search for a range (ex from 2016 to 2019)
- A button can also be included, so that the user can enter all the parameters first, and then hit search
