# CSS-Styled-Select
A bit of optimized CSS to style the html form select tag consistently across browsers.

## Goal
Trying to achieve as much customization as possible with cross-browser consistency while maintaining the usability and accessibility of the native select. Any extra elements and especially complete javascript replacement is therefor avoided.

## Usage
The only file you need is dist/styled-select.css. All other files in this repo are examples and source files not necessary for production use. Even the arrow image resides inside the CSS as an inline data-URI SVG.

Functionality and style are separated in the CSS to allow for easy customization (colors, sizing etc.).

## Browser support
* IE9+ (untested)

## Todo
* Add browser screenshots
* Find a way to transition the SVG arrow color on hover
* Find a way to make overflow ellipsis work in browsers other than Firefox
