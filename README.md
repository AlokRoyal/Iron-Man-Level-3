# Iron Man — Level 3

A p5.js game prototype that builds on the Iron Man platform mechanics. Move the character across a scrolling background, land on falling bricks, and collect diamonds to raise the score.

## Controls and objective

Use the left and right arrow keys to move and the up arrow to jump. Diamonds add to the on-screen score. Bricks are generated as moving platforms; continue navigating and collecting items.

## How the sketch is organized

sketch.js loads background, character, brick, and diamond images from images/. It creates sprite groups, updates movement and gravity in the frame loop, checks collisions, generates objects at intervals, and renders the score. Canvas dimensions and gameplay values are defined in the sketch.

## Run locally

Open index.html in a browser with images/, lib/, and CSS/ present. No package manager or build step is configured. Use a local static server if your browser blocks local asset loading.

## Technology

HTML5, CSS3, JavaScript, p5.js, and p5.play. The game keeps state in memory and does not use a backend or persistent scores.