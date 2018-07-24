# bowling_form
This repository contains sample HTML5 markup for the bowling alley reservation form. 

The form follow the wireframe/mock-up presented by CBK, and consists of 4 "steps" on one page.

1. Date picker element to select the day for which the user would like to reserve a bowling lane.
2. A table containing a list of available times for the two bowling lanes.
  * If the time has been reserved for both lanes, the input element will receive a "disabled" attribute.
3. Javascript updates the form as the user steps through, showing each new step.
  * Each "step" has a separate fieldset with an attribute of "disabled" and a class of "hidden". 
  * If you would like to show all the steps, simply remove the "hidden" class from the fieldsets and update any JS referencing it.
4. A success message appears upon completion.

Only the bowling form needs to be styled as the remainder of the page elements have already been styled as desired. JS file should not need editing unless CBK wishes to continue stripping out jQuery (I was in the process of doing so but ran out of time, sorry!) or wishes to update any behavior.

You will the bowling form markup will begin and end with HTML comments `<!-- that look like this -->`. 

All CSS should go into the `bowl.css` stylesheet.
