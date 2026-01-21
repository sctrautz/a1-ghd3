# Assignment 1 – D3 Lighthouse Scene

**Live Demo (GitHub Pages):**  
http://sctrautz.github.io/01-ghd3/index.html

## Description
For this assignment, I created a nighttime lighthouse scene using D3.js. The visualization shows a lighthouse on a beach with ocean waves, clouds, birds, and an animated lighthouse beam. My goal was to practice generating basic graphical primitives while keeping the code simple and fun.

The scene is built entirely from SVG elements created with D3, and it uses animation and layering to add visual interest beyond static shapes.

## Graphics Primitives Used
This project includes all required graphical primitives and various different colors to form a complete scene:
- **Rectangles:** sky, ocean, sand, lighthouse tower, lighthouse stripes, door
- **Circles:** moon, lighthouse windows, lighthouse light source, clouds
- **Lines:** ocean waves, birds
- **Polygons:** lighthouse roof, lighthouse beam, rock on the beach

## Interaction and Animation
- The lighthouse beam is animated using a repeating D3 transition that pulses its opacity.
- The beam is angled upward using a polygon shape to resemble a real lighthouse beam.
- The Birds and clouds add depth to the scene through layered composition.

## Screenshots

<img width="1440" height="808" alt="Screenshot 2026-01-21 at 2 42 39 PM" src="https://github.com/user-attachments/assets/4c0f2168-a646-4a91-ab6e-e067d92181e2" />

## Sources
- D3.js library: https://d3js.org/
- All code was written by me for this assignment. No external D3 templates were used beyond including the D3 library itself.

## Technical Achievements
- Implemented an animation to the lighthouse beam by pulsing its opacity.
- Used SVG polygon geometry to create a realistic light beam instead of a simple line.
- Organized the visualization into clear sections (background, foreground, details) to improve design and layering.

## Design Achievements
- Designed a nighttime color palette to emphasize contrast and make the lighthouse beam the focal point.
- Used repetition (lighthouse stripes, waves, windows) to create visual consistency.
- Added environmental details such as clouds and birds to improve realism and depth.
