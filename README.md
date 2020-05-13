# Project3_InteractiveForm
 
An interactive form for a fictional conference called "FullStack Conf."

This runs with or without Javascript. 

This project accomplished the following:

Creates and hides various error messages depending on outcome of validity

Functions using regex to check the following fields are valid;
    - Username, email, activities, creditcard number and CVV and zip code. 


On page load:
Puts cursor in the username field

Hide; Other job, color options, paypal and bitcoin wording, until needed. 

Adds a cost total for selected activites

Event Listeners:
- Job Role:
    When someone selects OTHER job a box appears below to give detail

- Colors:
    When a theme is selected the colors for that them are displayed as options in the next box. Tomato is default when I heart JS is selected

- Activities:
    When someone selects an activity, they can't then choose one at a conlifting time, based on data-day-and-time matching. 
    Conflicting events are greyed out and the checkbox is disabled.
    Totals for the activities are calculated and displayed at the bottom.
    Total is removed when activities are removed. 

- Payment:
    Corresponding details are selected based on what payment type is chosen. 

- Inputs:
    -Username isn't blank
    -Email is valid format
    When credit card is selected
    -Creditcard number is valid length and contains only numbers
    -Zipcode is 5 digits long
    -CVV number is 3 digits long
