#ColorSelect

This is a simple jQuery plugin, that turns a select box into a user friendly color picker.

## Installation

Just include colorSelect.js in your html. Optionally, also include the provided css file.

This is a jQuery plugin, so you obviously also need to include jQuery.

## Usage example

    <select id="color-select">
    	<option value="#990000">red</option>
    	<option value="#009900">green</option>
    	<option value="#000099">blue</option>
    </select>
    
    <script language="javascript" type="text/javascript">
        $('#color-select').colorSelect();
    </script>

The text inside the option-tags is not displayed, but it's good as a fallback.

## Styling

The plugin simply creates a tree of divs that you can style to your liking. Have a look at the provided css file for the defined classes.

## Demo

[click here](http://htmlpreview.github.com/?https://github.com/Lorenzschaef/colorSelect/blob/master/demo.html)