# UFO Analysis with JavaScript

## I. Overview of Project

### Background

Dana is a data journalist writing about her hometown McMinnville, Oregon. Her hometown is famous for UFO sightings and even has an annual gathering of UFO enthusiasts. For this project, I have been helping her analyzing and scraping a set of data in JavaScript format. We have created an app to deploy JavaScript functions to loop through and filter the data, and then created a HTML file to populate the data table using JavaScript. On the HTML file, we added a filter button to filter data on date. Finally, we also used Bootstrap and CSS stylesheet to customize the visualization.


### Purpose

The purpose of this challenge is to provide a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. Besides date, I will also add city, state, country and shape. In addition, I have removed the button and set the form to update automatically when the input of filter changes on the website. 

## II. Results -- Description of how to perform a search


### Structure:

![fullscreenshot](https://user-images.githubusercontent.com/84211948/131237166-d1447637-c5dd-4957-9df2-3202cd8b2f0b.png)

-	The very top part is a navigation bar with text “UFO Sightings”.
-	Right below vav bar is a jumbotron written “The Truth Is Out There” with an image background.
-	Next section has two parts of content: left section is a title “UFO Sightings: Fact of Fancy?” and a subtitle “Ufologists Weigh In”; right section contains a paragraph information.
-	The bottom left section is the filter input form, where users can input one or multiple filters by date, city, state, country and shape.
-	The bottom right section is the data table, which updates with filter inputs.

### Instruction:

**Click [HERE](https://weihaolun.github.io/UFO-Analysis/) to access to the website.**

-	In Filter Search section, input desired date，the table will update to results by that specific date.
  
    ![filter1](https://user-images.githubusercontent.com/84211948/131237250-6408858b-79d5-4e4b-a6ed-2eab73f8cd81.png)

-	Enter another one or multiple filters, press Enter, the data table will update to filtered data.
  
    ![filter1 2](https://user-images.githubusercontent.com/84211948/131237256-bd1067c8-44db-4fd1-8948-4ef3b89b914f.png)

-	Click top of the page “UFO Sighting” in nav bar to reset the filter form.
  
    ![Screen Shot 2021-08-28 at 4 59 41 PM](https://user-images.githubusercontent.com/84211948/131237263-12bef0b1-d976-43b2-94f4-388e2c73a24f.png)


## III. Summary

### Drawback

The users must have basic knowledge of the data before conducting a search. For example, the user must know the available date, cities, states, countries, and shapes in the dataset in order to get data returned. If the users randomly type a city she/he wants to search for, for instance, Honolulu, she/he will get nothing returned. 

### Recommendations

-	To address the drawback above, it would be better if there’s a drop-down menu/list for each filter. Therefore, the users will know available elements within each filter to avoid typing invalid input. 
-	It would be a more optimal user experience if there is a button in Filter Search Section.
-	Another recommendation for development in the future is that we can remove the Filter Search Section and implement drop-down filter menu on the table header. Each filter has a drop-down, users and filter the data directly in the table.


