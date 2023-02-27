# Mars_News Overview
Using JavaScript to create a table to organize UFO data that is stored as a JavaScript array, or list. This table will have the ability to filter data based on certain criteria and will be created using JavaScript as the primary coding language. It was necessary to create filters to make this table fully dynamic, meaning that it will react to user input, and then place the table into an HTML file for easy viewing.

# Strategy
  We began by learning simple JavaScript functions and transforming these functions into arrow functions. Familiarity with both types—traditional functions and arrow functions—are important because both are used in development, while arrow functions keep our code clear and readable, traditional functions are necessary in some cases as well. We continued by training with foor loops since iteratating through items is a key component in coding languages. This then allowed us to created Dynamic Tables by adding forEach functions into our table alongside "If" statements. Once we had our Dynamic Tables set correctly, the last step was to build the webpage. We added adding a link to Bootstrap's content delivery network (CDN) on our HTML file along with adding our data and styling our webpage through our CSS file.

# Deliverable 1: Filter UFO sightings on Multiple Criteria
  Once the webpage and dynamic table are working as intended, we need to provide a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. We have the ability to search by date, but we now we add table filters for the city, state, country, and shape.
 
 # Process
  Using JavaScript we created a new function that saves the element, value, and id of the filter that was changed. Then, created a new function to loop through the dataset and keep only the results that match the search criteria. The webpage will be updated with the search criteria after pressing "Enter". The first step was to create four more list elements: city, state, country, and shape. Each element should have the same "id" as the object properties in the js file. Next we created an empty filters variable to keep track of all the elements that change when a search is entered. We followed this by modifying the event listener so that it detects a "change" on each input element and calls the updateFilters() function. We then created multiple variables that saved the element that was changed, saved the value of the changed element's property, and the attribute of the changed element's id. We then needed if-else statements to check the value changed by the users input, and create code to filter the table based on the imput. Next was to loop through the filters object and store the data that matches the filter values in the variable we just created. Lastly, we rebuilt the table with the filtered data by passing the same variable. Now our web app is ready to be deployed.

# Results 
# How many months exist on Mars? 
1,867 

# Which month, on average, has the lowest temperature? The highest? 
On average, the third month has the coldest minimum temperature on Mars, and the eighth month is the warmest. But it is always very cold there in human terms!
<img width="437" alt="Screen Shot 2023-02-07 at 10 44 49 AM" src="https://user-images.githubusercontent.com/117120227/217337163-464c09b5-3173-4fff-931e-7548c9d958c7.png">

# Which month, on average, has the lowest atmospheric pressure? The highest? 
Atmospheric pressure is, on average, lowest in the sixth month and highest in the ninth.
<img width="437" alt="Screen Shot 2023-02-07 at 10 45 08 AM" src="https://user-images.githubusercontent.com/117120227/217337229-95afbb67-7505-49cb-8766-598fefb4e5fb.png">

# How many terrestrial days exist in a Martian year? A visual estimate within 25% was made. 
The distance from peak to peak is roughly 1425-750, or 675 days. A year on Mars appears to be about 675 days from the plot. Internet search confirms that a Mars year is equivalent to 687 earth days.

<img width="437" alt="Screen Shot 2023-02-07 at 10 45 21 AM" src="https://user-images.githubusercontent.com/117120227/217337262-7c9a9dba-a7f3-441c-a442-143a30d10034.png">



