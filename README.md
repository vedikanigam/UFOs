# UFOs

## Overview of the Analysis
Dana is a journalist who is creating a webpage about UFO sightings from a javascript data file about UFOs. This webpage will have a dynamic table that will change based on user inputs. 

### Purpose
The purpose of this project is to help Dana add filters for multiple criteria at the same time. For this project, we will insert javascript into html to get the desired output.

## Results

### Filter by country
A user can input the criteria - date, city, state, country, shape - in any order. For instance if someone wants to find out about sightings in California, US on 01/04/2010 the user can first enter 'US' in 'Enter a Country' search window as shown in the image below.  

![Country]()

### Filter by state
Then to find sightings in California, the user can input 'ca' in 'Enter a State' search window. Alternatively, the user can input the state without selecting the country and that would work as well.   

![State]()

### Filter by date
Finally, to find the sightings on 01/04/2010 the user can input the date in 'Enter a date' window and table wouls show all the sightings on 01/04/2010 in California, US. 

![Date]()

## Summary 
One drawback of this design is that a user cannot select multiple cities, states or countries in the search window. Secondly, the input text has to match exactly with the data in the table. If a user inputs state in upper case, they will not get any result.
 
### Recommendations
A dropdown menu with the options available may be a better way for the user to know what exact data is available. Secondly, a calender with starting and ending date that matches with the dates for which sightings are available in "Enter a date" search window may be easier in picking a date. 
