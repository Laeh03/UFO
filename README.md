# UFO Sightings

## Resources 
Data Source: ufo_startercode.js; data.js; index.html; nasa.jpg

Software: JavaScript; Visual Studio Code; Bootstrap; CSS

## Overview
------------------

This project provides the information of UFO sightings by creating a webpage with a dynamic table. Allowing users to filter for multiple criteria such as events date, city, state, country, and shape all at the same time.

## Results
Using JavaScript and HTML to modify the code in our index.html file, we created more table filters. In addition to the date filter you created in this module, we added filters for the city, state, country, and shape, as shown in the following image:

![Screenshot (109)](https://user-images.githubusercontent.com/64225504/134253055-7571785b-134f-4cd8-a09a-6b7276fea95f.png)

* The list element that creates the button was removed, therefore five list elements for filtering in the index.html file were created.
* The event listener was modified to detect changes to each filter in the app.js file.
* The updateFilters() function saves the element, value, and the Id of the filter that was changed.
* The filterTable() function loops through all of the filters and keeps any data that matches the filter values.
* The webpage filters the table correctly based on user input.

Having filters helped limit how much data was needed by date, city, state, country, and shape or a combination of all or any. To ensure that the filters worked, I tested the following combinations: date 1/1/2010.

![Screenshot (111)](https://user-images.githubusercontent.com/64225504/134256014-7cebd0d4-11e9-490c-998e-dc8dfed9df5a.png)

These are the steps to filter through the data. 

One would select the open field of their choice as the placeholder suggests.
Selecting "enter" after the input or using the "filter" button that was added back.
Results should be provided in the table format as listed in the screenshot.
It would be suggested to add a "reset" or "clear" button to clear the previous search

## Summary
One drawback from this new design would be, This only had data that was given as of January 2010; it would have been good to see a year or a dynamic webpage where the data was real-time. Another drawback, was that the webpage was on the localhost server, it limited access to users and visibility. It was suggested to use Github pages, however once posted, the code, access, visibility were no longer private. Anyone with internet/browser access can view the webpage and all of the components.

Recommendations for further development: Adding the filter button back helped give the user engagement of clicking a button to filter the data. Adding a reset or clear button would also be helpful. Fixed Headers and a scrollable feature within the table would also be helpful for those searches that yield a larger result such as the state "ca". I may even suggest a dropdown selection for the following elements: city, state, country and shape.
