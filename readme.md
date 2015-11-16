#ColorSelect

This is a simple jQuery plugin, that turns a select box, that contains hex-color-codes as its options, into a nice, user friendly color picker.

## Installation

Just include colorSelect.js in your html. Optionally, also include the provided css file.

This is a jQuery plugin, so you obviously also need to include jQuery.

## Usage example

    <select id="color-select">
    	<option value="#900">red</option>
    	<option value="#090">green</option>
    	<option value="#009">blue</option>
    </select>
    
    <script>
        $('#color-select').colorSelect();
    </script>

The text inside the option-tags is not displayed, but it's good as a fallback.

## Styling

The plugin simply creates a tree of divs, that you can style to your liking. Have a look at the provided css file for the defined classes.