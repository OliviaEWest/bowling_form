# bowling_form
This repository contains sample HTML5 markup for the bowling alley reservation form. 

The form follow the wireframe/mock-up presented by CBK, and consists of 4 "steps" on one page.

1. The form can be included in an existing page as-is and the included script will work fine. If the form markup is not used, the javascript file will need to be updated to fit your existing markup. The form can be found between the HTML comments `<!-- that look like this -->` or use the markup in `just-the-form.html`.
2. Date picker element to select the day for which the user would like to reserve a bowling lane.
3. A table containing a list of available times for the two bowling lanes.
    * If the time has been reserved for both lanes, the input element will receive a "disabled" attribute.
4. Javascript updates the form as the user steps through, showing each new step.
    * Each "step" has a separate fieldset with an attribute of "disabled" and a class of "inactive". 
    * If you would like to "grey out" an inactive step, simply update the CSS file for selector (.inactive).
5. A success message appears upon completion.

All CSS should go into the `bowl.css` stylesheet.
