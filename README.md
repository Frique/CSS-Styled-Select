# CSS-Styled-Select
A bit of optimized CSS to style the html form select tag consistently across browsers.

## Goal
Trying to achieve as much customization as possible with cross-browser consistency while maintaining the usability and accessibility of the native select. Any extra elements and especially complete javascript replacement is therefor avoided.

## Usage
The only file you need is dist/styled-select.css. All other files in this repo are examples and source files not necessary for production use. Even the arrow image resides inside the CSS as an inline data-URI SVG.

Functionality and style are separated in the CSS to allow for easy customization (colors, sizing etc.).

## SVG
The arrow is a homemade SVG file of 2 triangles (see attached .svg file), minified through https://jakearchibald.github.io/svgomg/ and encoded via http://dopiaza.org/tools/datauri/index.php to make it work in IE9+ and Firefox. Base64 encoding would work fine but it makes the snippet a bit longer. To change the arrow's color, change the #ddd in the SVG file to your preferred color and re-encode it before pasting it into your CSS.

## Browser support
* IE9+ (untested)

## Todo
* Add browser screenshots
* Find a way to transition the SVG arrow color on hover
* Find a way to make overflow ellipsis work in browsers other than Firefox

## Known issues
* IE8,9 = Native arrow shows
* IE8,9 = Native arrow misplaced to the left
* IE8 = SVG arrow doesn't show
* IE8 = Text vertically aligned to the bottom
