# UFOs

## Project Overview
Any amount of analysis, no matter how precise or complex, is useless if it cannot be communicated. We can use data visualizations to present a story using data that is clear, accessible, and consistent. Even persons with minimal data fluency may analyze data using visualizations.

We will use Javascript to create a table that organizes UFO data that is stored as a JavaScript array, or list, in this repository. This table will be able to filter data based on specific criteria and will be written in JavaScript.

### Coding Goals
* Build and deploy JavaScript functions, including built-in functions.
* Convert JavaScript functions to arrow functions.
* Build and deploy forEach (JavaScript for loop).
* Create, populate, and dynamically filter a table using JavaScript and HTML (convert a Javascript array into an HTML Table)

### Results
The resulting homepage is a reasonably user-friendly display of ufo sighting data, complete with a filter table that lets viewers to easily filter by date, city, state, and shape of the UFO sighting. The following is an unfiltered global view.

![global view](/Images/img_1.png)

As you edit the form field entries, the presented results are dynamically filtered. Because the tables update in real time, there is no need for a Submit or Refresh button. The filter selection can be broad, such as picking simply a country and state, such as the United States of America and California.

![filter](/Images/img_2.png)

Filter results can be reduced further by defining a date, a city in a single state, or focusing on a certain shape type, such as "bright."

![filters](/Images/img_3.png)

## Summary
Users can search for numerous criteria at once on our existing webpage, and there is no need for a submit button. There are some disadvantages, however. The primary flaw is that the search choices don't give you a good picture of what you can look for. The existing fields are all text boxes, which might lead to numerous user errors or misinterpretation. This unproductive and time-consuming data analysis.

***Drawbacks***
* The method of filtering is case sensitive. As a result, if a user typed anything in upper case, the search results would be incorrect. For example, if the user typed "Ventura" instead of "ventura," the filtered results would not include the city.
* Because the user may not be sure when the data was collected, they may enter dates for which we do not have data. The user should be able to select a date by clicking on a calendar.



