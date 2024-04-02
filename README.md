# Hover Effect

This repository demonstrates two methods for creating a hover effect on buttons using HTML, CSS, and JavaScript.

## Method 1: JavaScript

### Description
This method uses JavaScript to create a hover effect on buttons by changing their background and border styles dynamically based on mouse movement.

### Implementation
The JavaScript code selects all buttons with the class `win-btn` using `document.querySelectorAll`. It then attaches event listeners for `mouseleave` and `mousemove` to each button. 
- On `mouseleave`, the background and border styles are reset to default.
- On `mousemove`, a radial gradient effect is applied to the button background and border based on mouse position within the button.

### Usage
1. Include the JavaScript code in your HTML file or script.
2. Ensure that buttons you want to apply the hover effect have the class `win-btn`.

## Method 2: CSS

### Description
This method uses pure CSS to create a hover effect on buttons by applying a radial gradient overlay to simulate a spotlight effect.

### Implementation
The CSS code applies the hover effect using pseudo-elements (`::after`) and CSS transitions. 
- The pseudo-element `::after` creates a radial gradient overlay that expands from the center of the button upon hovering.
- CSS transitions are used to animate the expansion of the overlay.

### Usage
1. Include the CSS code in your HTML file or link it externally.
2. Ensure that buttons you want to apply the hover effect have the class `win-btn`.

## Examples
- [JavaScript Method](./js-method-example.html)
- [CSS Method](./css-method-example.html)

Feel free to explore the examples to see each method in action!

