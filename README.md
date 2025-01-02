# Tailwind CSS Hover Issue on Dynamic Content

This repository demonstrates an uncommon bug in Tailwind CSS where hover effects fail to apply to elements added to the DOM after the initial render.

## Bug Description

The provided `index.js` file contains a simple React component that increments a counter. A button with a Tailwind CSS hover effect is used to trigger the increment. However, the hover effect only works reliably when the button is present from the initial page load. If you add a new button dynamically, the hover styles will not be applied correctly.

## Reproduction

1. Clone this repository.
2. Run `npm install` to install dependencies.
3. Run `npm start` to start the development server.
4. Observe that the button's hover effect works as expected.
5. Explore how to make the hover effect work dynamically, as discussed in the solution.