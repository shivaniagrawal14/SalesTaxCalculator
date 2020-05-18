<h1 align="center">
  Sales Tax Calculator
</h1>
<p align="center">
  A calculator which calculates sales tax and tax rate with a minimalist design.
</p>


## What is this and How it is created?
I write a very simple HTML and CSS UI for a sales tax calculator web application with the addition of some simple JavaScript behaviors to my HTML/CSS file which will enable the buttons to work and calculate the tax and total for you.

* Use the included wireframe mockup as a guide to what components should be in the
app UI and a general layout.

* UI needs a form with 4 text inputs and the appropriate labels and text instructions.
There needs to be two buttons, use html button elements. 

* The sales tax and total input boxes are disabled so a user cannot type in any
values. 

* Added a <script> tag section at the end of body section in the HTML page for the
JavaScript. 
  
* Added three event handlers (functions). One will be for the
calculate button, one will be for the clear button, and one will setup and bind the event
handlers to the buttons when the page loads.

* Defined an event handler function that will be connected to the calculate button. This is
where I should do all my calculations and then put the results in the sales tax and
total fields. 

* Defined an event handler function that will be connected to the clear button. In this
function I should clear out all the fields and then put the cursor back in the subtotal
field so it is ready for new input. 

* Defined an event handler function that will be used to initialize or setup the app. This
event handler only needs code to bind the other two event listeners to the buttons. In
this function add event listeners, for click events, to the two buttons and call the correct
event handler function for each.

* Added an event listener to the window object to listen for the load event and call the
initialize/setup event handler function. This way when the page loads that will trigger
JavaScript to setup the other two buttons click handlers.

* Added basic validation to the input from the subtotal and tax rate field. It dispayed any errors
with validation in an alert box which makes sure the the message in the alert box is clear and tells
the user what is wrong with their input. 

* Basic validation which I generated
The subtotal value needs to be a valid positive number [x > 0]. 
The tax rate value must be a number greater than 0 and less than or equal to 20 [0 < x <= 20].
