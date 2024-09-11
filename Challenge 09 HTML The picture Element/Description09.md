# HTML Challenge: The `<picture>` Element

## Objective
The goal of this challenge is to use the HTML `<picture>` element to display different images based on the device or screen size, allowing for flexibility in image selection.

## Requirements
- Use the `<picture>` element to include multiple `<source>` elements with different image sources.
- Each `<source>` element should use the `srcset` attribute and, optionally, the `media` attribute to specify the most suitable image for different conditions (e.g., screen size, device).
- Include a fallback `<img>` element as the last child of the `<picture>` element, which will be used by browsers that do not support the `<picture>` element or if none of the `<source>` tags match.

## Example Scenario
You will create a responsive image for a website banner. The website should display different versions of the banner based on the screen size: one for mobile devices, one for tablets, and another for desktop computers.

This example is adapted from the HTML `<picture>` element tutorial found at [W3Schools HTML Picture Element](https://www.w3schools.com/html/html_picture.asp).

## Bonus
- Experiment with using different image formats (e.g., WebP, PNG, JPEG) for better browser support.
