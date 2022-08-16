# UFOs

## Module 11: UFO Sightings with JavaScript
---
### Overview of Project
In this module, I used UFO data that's stored as a JavaScript array or list to create a table analysis of UFO sightings that were recorded from Jan 1-13 of 2010. In order to filter the data, I used Javascript functions to loop through the data to build a table that can be used as a customized dashboard. The customizations include filters with event listeners that will record the information when an element has changed. 

In this challenge, we will provide a more in-depth analysis of UFO sightings by allowing users to filter for several elements, such as the city, state, country, and shape. Filters can be applied in many ways, so in this exercise, we reviewed how to create, populate, and dynamically filter a table based on the user's input with a select criteria.

### Purpose

In this module, I used HTML, Bootstrap and CSS to read the Javascript code and create an interactive webpage that is easy to view, includes filters, images, and a synopsis of the topic.

---
### Results: 
*Describe to Dana how someone might use the new webpage by walking her through the process of using the search criteria. Use images of your webpage during the filtering process to support your explanation.*

**This is how the filters appear when you first land on the page:**
![UFOpg](https://user-images.githubusercontent.com/68654746/184734823-3e19081a-292a-4b4b-8d21-9d6e8837c72c.png)
- You will notice that a "Filter Search" section has been added with placeholder values.

- You can filter by one or all of the search criteria shown. 
  - for instance, if you search by "state", you will see that the table will update to show the reported sightings that were recorded for that specific state. There are many UFO sightings in California. 
![UFO_cali1](https://user-images.githubusercontent.com/68654746/184754738-c9a550d0-4a1e-4b07-964c-041b107869a8.jpg)
![UFO_cali2](https://user-images.githubusercontent.com/68654746/184754800-c0404254-5faf-4351-b862-17ed4b3cf89f.jpg)

- If you delete your previous entries and enter values in "Country" and "Shape", the table will update using your new criteria.
  - for example... US and fireball
![newfilters](https://user-images.githubusercontent.com/68654746/184759477-816f3e0e-d885-4b59-8bed-16254a756a5c.jpg)


### Summary: 
*In a summary statement, describe one drawback of this new design and two recommendations for further development.*

Some drawbacks...
- The UFO data is pretty limited and outdated since it is not linked to a live source. 
- In order to avoid an empty table, the user must know specific values of dates, cities, or shapes to look up. However, some values such as shapes like "chevron" and "formation" might not be as intuitive to search. 
- The search field is case-sensitive and must all be in lower-case without any spaces at the end. If you do not enter exactly how the data is stored, it will not allow for any partial entries. This may make it challenging for the user how to enter in information other than the "default" values already given.

Recommendations...
- Since our data is limited in many ways, such as time and location, we could pull in more data from a live source that provides current and archived data. 
- We can improve the user's experience by adding additional customizations, such as click-buttons, dropdown list, and auto-fill values that may assist the user explore the data and make the page more interactive.
