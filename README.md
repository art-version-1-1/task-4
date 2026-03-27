# Task 4 - Do Not Click

A simple, interactive web page featuring an image and a clickable button styled with modern CSS techniques.

## Project Overview

This project demonstrates:
- Basic HTML structure with semantic markup
- CSS styling with viewport-relative units (vw/vh)
- Box model management using `box-sizing: border-box`
- Responsive button styling with gradient background and hover effects

## Files

- **index.html** - Main HTML file with image and button elements
- **style.css** - Stylesheet with responsive design using viewport units and box-sizing property

## Features

### Layout
- Centered image (50% width of viewport)
- Centered button with gradient background
- Black background

### Styling Details
- **Box-sizing**: All elements use `box-sizing: border-box` to ensure padding and borders are included in total width/height calculations
- **Margins**: Uses viewport units (vw/vh) instead of percentages for consistent spacing across different screen sizes
  - Image: `margin-left: 25vw`, `margin-top: 10vh`
  - Button: `margin-left: 25vw`, `margin-right: 25vw`
- **Button**: Gradient background (pink to blue) with hover effect that changes to dark background with white text

## How to Use

1. Open `index.html` in a web browser
2. Click the "Click Me" button to be redirected to a YouTube video
3. The page is fully responsive and adapts to different viewport sizes

## CSS Viewport Units

- **vw** (viewport width): 1vw = 1% of viewport width
- **vh** (viewport height): 1vh = 1% of viewport height

These units are used instead of percentages to ensure margins scale consistently with the viewport rather than the parent container.
